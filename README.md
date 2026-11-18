> **Community fork.** Microsoft retired the Azure Storage PHP client libraries on 17 March 2024 and archived the original
> repository. This fork (`brasizza/azure-storage-common`) keeps the library working and receives fixes. It is a drop-in
> replacement for `microsoft/azure-storage-common`: the `MicrosoftAzure\Storage\...` namespace is unchanged.
> Not affiliated with or endorsed by Microsoft. Original code © Microsoft Corporation, MIT License.
>
> ```bash
> composer remove microsoft/azure-storage-common
> composer require brasizza/azure-storage-common
> ```

# Microsoft Azure Storage Common PHP Client Library (Deprecated)

For more details on the retirement and alternatives to using this project, visit [Retirement notice: The Azure Storage PHP client libraries will be retired on 17 March 2024](https://aka.ms/AzStoragePHPSDKRetirement).

This project provides a set of common PHP code shared by Azure Storage Blob, Table, Queue and File PHP client libraries. For how to access Microsoft Azure Storage services (blobs, tables, queues and files), please refer to the [Microsoft Azure Storage PHP Client Library](https://github.com/Azure/azure-storage-php). For documentation on how to host PHP applications on Microsoft Azure, please see the [Microsoft Azure PHP Developer Center](http://www.windowsazure.com/en-us/develop/php/).

[![Latest Stable Version](https://poser.pugx.org/microsoft/azure-storage-common/v/stable)](https://packagist.org/packages/microsoft/azure-storage-common)

> **Note**
>
> * This [repository](https://github.com/azure/azure-storage-common-php) is currently used for releasing only, please go to [azure-storage-php](https://github.com/azure/azure-storage-php) for submitting issues or contribution.

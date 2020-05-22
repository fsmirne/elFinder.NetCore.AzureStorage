<img src="https://github.com/fsmirne/elFinder.NetCore.AzureStorage/blob/master/_Misc/Logo.png" alt="Logo" width="350" />

## Instructions

1. Install the NuGet package: https://www.nuget.org/packages/elFinder.NetCore.AzureStorage/

2. Look at the [demo project](https://github.com/fsmirne/elFinder.NetCore.AzureStorage/tree/master/elFinder.NetCore.Web) for an example on how to integrate it into your own project.

## Azure Storage Connector

In order to use the Azure Storage Connector

1. Open your **Startup.cs** file and look for the following lines:

```
AzureStorageAPI.AccountName = "[Name]";
AzureStorageAPI.AccountKey = "[Key]";
```

> Replace `[Name]` and `[Key]` with the appropriate values for your Azure account.

2. Change the **root directory** in the `AzureStorageController` from `test` to the name of your Azure file share.

## Dependencies

This plugin depends on [**elFinder.NetCore**](https://github.com/gordon-matt/elFinder.NetCore) from [Matt Gordon](https://github.com/gordon-matt)

# AZ-203: Develop Azure Platform as a Service Compute Solutions (20-25%)

You want to have a solid foundation in working with the Azure Storage APIs. This includes blob, table, etc.

## Storage Accounts

* I would say familiarize yourself with the [overall security plane of storage accounts](https://docs.microsoft.com/en-us/azure/storage/common/storage-security-guide#management-plane-security). You don't have to memorize, but you should recognize essentials and be able to understand the mechanical relationships

* Know cold the foundational objects and their methods, including the [CloudStorageAccount](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started/blob/master/BlobStorage/Common.cs). 
Use Visual Studio's Intellisense and looking at the definition to get a sense for the method overloads that are available to you. Take the [GettingStarted.cs](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started/blob/master/BlobStorage/GettingStarted.cs) and 
literally put it into a side by side on a screen and type out the whole thing. This will get your brain's muscle memory working. 

## Blob Storage
* Start by reading through how to [use shared access signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1). 
* Next, focus your attention on the getting started with [Azure Blob Storage Samples for .NET](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started). 

## Azure Tables

* First, review [understanding the data model](https://docs.microsoft.com/en-us/rest/api/storageservices/understanding-the-table-service-data-model)
* Focus on [performing queries with the Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-query-table) using the C# SDK at a minimum.
* Understand how [Cosmos DB relates to Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/table-introduction). Once you have a foundation, 
* [build a Table API app with .NET and Azure Cosmos DB] https://docs.microsoft.com/en-us/azure/cosmos-db/create-table-dotnet


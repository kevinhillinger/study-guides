# AZ-203: Develop for Azure storage (15-20%)

You want to have a solid foundation in working with the Azure Storage APIs. This includes blob, table, etc.

## Develop solutions that use storage tables
* First, review [understanding the data model](https://docs.microsoft.com/en-us/rest/api/storageservices/understanding-the-table-service-data-model)
* Focus on [performing queries with the Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-query-table) using the C# SDK at a minimum.
* Understand how [Cosmos DB relates to Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/table-introduction). Once you have a foundation, 
* [build a Table API app with .NET and Azure Cosmos DB] https://docs.microsoft.com/en-us/azure/cosmos-db/create-table-dotnet

## Develop solutions that use Cosmos DB storage
* Consistency levels may be covered, so you want to [understand the scenarios where each apply](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels). The baseball explaination may help.
* [Choosing the right consistency level](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels-choosing). Read the further reading options on the documentation. It may help.
* Go through the [].NET App tutorial on consuming Cosmos with the SQL API](https://docs.microsoft.com/en-us/azure/cosmos-db/create-sql-api-dotnet)
* Once you have the app created, practice with the [SQL Commands](https://docs.microsoft.com/en-us/azure/cosmos-db/how-to-sql-query)

## Develop solutions that use a relational database
 > *Provision and configure relational databases, Configure elastic pools for Azure SQL Database, Create, read, update, and delete data tables by using code*

* [Understand the options for database security](https://docs.microsoft.com/en-us/azure/security/azure-database-security-best-practices). Focus on the different ways to authenticate to SQL Server as well as the options available using Azure AD.
* Read through the [connectivity guidance to SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-connectivity-issues)

Provision and configure relational databases
Configure elastic pools for Azure SQL Database
Create, read, update, and delete data tables by using code

## Develop solutions that use blob storage

* Start by reading through how to [use shared access signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1). 
* Next, focus your attention on the getting started with [Azure Blob Storage Samples for .NET](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started). 
* Familiarize yourself with the [overall security plane of storage accounts](https://docs.microsoft.com/en-us/azure/storage/common/storage-security-guide#management-plane-security). You don't have to memorize, but you should recognize essentials and be able to understand the mechanical relationships
* Know cold the foundational objects and their methods, including the [CloudStorageAccount](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started/blob/master/BlobStorage/Common.cs). 
* Use Visual Studio's Intellisense and looking at the definition to get a sense for the method overloads that are available to you. Take the [GettingStarted.cs](https://github.com/Azure-Samples/storage-blob-dotnet-getting-started/blob/master/BlobStorage/GettingStarted.cs) and literally put it into a side by side on a screen and type out the whole thing. This will get your brain's muscle memory working. 



---
page_type: sample
languages: java
products: azure
services: Cosmos-DB
platforms: dotnet
author: yaohaizh
---

# Create a DocumentDB and configure it for high availability using C# #

          Azure CosmosDB sample -
           - Create a CosmosDB configured with a single read location
           - Get the credentials for the CosmosDB
           - Update the CosmosDB with additional read locations
           - add collection to the CosmosDB with throughput 4000
           - Delete the CosmosDB


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/cosmosdb-dotnet-create-documentdb-and-configure-for-high-availability.git

    cd cosmosdb-dotnet-create-documentdb-and-configure-for-high-availability
  
    dotnet build
    
    bin\Debug\net452\ManageHACosmosDB.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
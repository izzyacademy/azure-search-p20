# Azure Search P20 Artifacts

You can use the [post man scripts here](https://github.com/izzyacademy/azure-search-p20/blob/master/P20AzureSearch-Collection.json) to create an index, add documents to the index and run queries against the index.

## Postman Environment Variables to Define

You will need to define the following variables in your postman environment:
- QueryApiKey
- AdminApiKey
- serviceName
- apiVersion
- indexName

### Contents of the Variables

Variable | Example | Description
--- | --- | ---
*QueryApiKey* | **079D3CCA69A550B2E4D8733F65D89590** | The admin api key for admin operations
*AdminApiKey* | **079D3CCA69A550B2E4D8733F65D89591** | The query api key for read only queries
*serviceName* | **isp20demo** | The name of your Azure Search service
*apiVersion* | **2017-11-11** | The API version you are using
*indexName* | **hotels** | The name of the Azure Search index.

## Relevant Links

### Downloading and Installing Postman
https://www.getpostman.com/docs/v6/postman/launching_postman/installation_and_updates

### Setting up Variables in Postman
https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables

### Creating and Index
https://docs.microsoft.com/en-us/rest/api/searchservice/index-operations

### Indexing Via REST API
https://docs.microsoft.com/en-us/azure/search/search-import-data-rest-api

### Supported Data Types
https://docs.microsoft.com/en-us/rest/api/searchservice/supported-data-types

### Querying the Search Index
https://docs.microsoft.com/en-us/rest/api/searchservice/lucene-query-syntax-in-azure-search

https://docs.microsoft.com/en-us/azure/search/search-query-rest-api

### Pricing Tiers
https://docs.microsoft.com/en-us/azure/search/search-sku-tier

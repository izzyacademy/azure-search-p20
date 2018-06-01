# Azure Search P20 Artifacts

You can use the [post man scripts here](https://github.com/izzyacademy/azure-search-p20/blob/master/PostMan-Collection.json) to create an index, add documents to the index and run queries against the index.

## Variables to Define

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

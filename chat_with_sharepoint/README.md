### Chat With SharePoint

To enable a chat with SharePoint using Azure Cognitive Search, you need to wire a few components together.  First, implement the solution in this repo - https://github.com/Azure-Samples/azure-search-openai-demo.

Follow these steps once that repo is deployed:

1. Enable the SharePoint connector for Azure Cognitive Search.
2. Implement this Skill within the index using the connector to create an indexer.  
    - https://learn.microsoft.com/en-us/samples/azure-samples/azure-search-power-skills/azure-open-ai-embeddings-generator/
3. Remap the fields in the skill to the appropriate fields in the index.
4. Test your search


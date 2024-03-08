# MultimodalChatbot-AzureSearchComputerVision

### This is image retrieval multi modal RAG pipeline by utlizing Azure search and Computer vision Florence foundation model which can results text and relevant images as completion to the user's query.
### Here are the steps that I had followed to creat this pipeline.
1. Install and import necessary packages
2. Defined sequence of functions to extract the text and images separately from input pdf document.
3. Defined utility functions to create embeddings for text and images using Azure computer vision florence model.
4. Data preparation
5. Creating Azure cognitive search with dataframe content
6. Search results


### In order to run your application, you should have the following credentials of Azure Computer Vision and Azure Cognitive Search in your ".env" file.
#### Azure computer vision
    key = os.getenv("AZURE_CV_KEY")
    endpoint = os.getenv("AZURE_CV_ENDPOINT")


#### Azure Cognitive Search
    cs_key = os.getenv("COG_SEARCH_ADMIN_KEY")
    cs_endpoint = os.getenv("COG_SEARCH_ENDPOINT")

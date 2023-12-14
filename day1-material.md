# Microsoft AI Workshop

## Day 1

### Environment Set Up

You need an Azure Subscription to follow the steps below.
In the subscription, you must have enough access to create resources.

> Some services, such as Azure OpenAI, require prior approval. Please make sure to submit a request in advance to have the resources ready for the workshop.

1. Create a resource group to host all resources.
2. In your resource group, deploy an instance of Azure OpenAI. 
    1. Once created, visit the playground page and deploy the following models:
    - `gpt-4-32k` or `gpt-4` (if you have access to GPT4)
    - `gpt-35-16k` or `gpt-35` (if you cannot deploy gpt-4)
    - `text-embedding-ada-002`
    2. Take note of the deployment names and your OpenAI service endpoint and key in `.env` file.
3. In your resource group, deploy an instance of Document Intelligence.
    - Take note of endpoint and key in `.env` file.
4. In your resource group, deploy an instance of Azure AI Search.
    - Take note of endpoint and admin key in `.env` file.
5. In your resource group, deploy a storage account.
    - Once provisioned, create a blob container in your account.
    - Take note of storage account name and container name in `.env` file.

## Notebook 1
In this notebook you familiarize yourself with Azure OpenAI.
Please go through [the notebook](./101-deep-dive-openai.ipynb).
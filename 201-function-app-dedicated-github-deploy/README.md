# Provision a function app with source deployed from GitHub

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/PublicLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/PublicDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/FairfaxLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/FairfaxDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/BestPracticeResult.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/201-function-app-dedicated-github-deploy/CredScanResult.svg" />&nbsp;

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fazure%2Fazure-quickstart-templates%2Fmaster%2F201-function-app-dedicated-github-deploy%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-function-app-dedicated-github-deploy%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true"/>
</a>

## Overview

This template deploys a Function App hosted in a new dedicated App Service Plan. The Function App has a child resource that enables continuous integration and deploys the function code from a GitHub repository.

This template deploys the following resources:

- App Service plan
- Storage Account
- Function App
    - App Settings Configuration
    - Source Control Deployment

## Azure Functions

> Azure functions is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it. For more information about Azure Functions, see the [Azure Functions Overview](https://azure.microsoft.com/en-us/documentation/articles/functions-overview/).

- [Microsoft Learn Functions Modules](https://docs.microsoft.com/learn/browse/?products=azure-functions)
- [Microsoft Function Pricing](https://azure.microsoft.com/pricing/details/functions/)
- [Microsoft Function Documentation](https://docs.microsoft.com/en-us/azure/azure-functions/)

## Miscellaneous

``Tags: app-service, function, github``


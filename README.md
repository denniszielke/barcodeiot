---
services: barcodeiot
platforms: c#
author: denniszielke
---


## Deploying this sample
1. Deploy the arm template in arm/template.json to azure

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdenniszielke%2Fbarcodeiot%2Fmaster%2Farm%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>  

It will deploy the following resources
- Azure Web App
- Application Insights
- Cosmos DB
- Azure Function
- Code from github to the WebApp
- Configuration from all resource to environment variables in the web app and function

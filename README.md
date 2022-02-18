# Bootstrap Demos

## Azure Devops / App Service Workaround for Static Website

### The Plan
* Teach students how to colloborate on Azure Devops using a static website.

### The Problem
* Free on Azure Devops doesn't allow you to create a build pipeline to an Azure App Service.
* You need to request access from Microsoft (2-3 working days).

### The Solution
* Create a server deployment using Azure App Service from Azure Repos.
* This Node app will serve static HTML pages from the view folder and it's subfolders.

### Steps

* Import this repo into Azure Devops.
* Create an App Service on the Azure Portal.
* Configure your Azure Repo as the deployment source for your App Service.
* Update the HTML files on your Azure Repo to update your App Service. 


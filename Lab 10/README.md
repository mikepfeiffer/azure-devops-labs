# Lab 10 - Blue-green Deployments with Azure App Service and GitHub

Deploy a Web App to Azure:

1. Create a new App Service in the Azure Portal (Web App) Make sure to select at least a Standard tier App Service Plan
2. Use the App Service Editor to customize the main home page and add the following code to the body of the page:
```
<h1>This is version 1.0.0 of the web app</h1>
```
3. Navigate to the url for your web app to confirm the changes

Create a "Dev" Deployment Slot

1. In the portal, create a deployment slot in your Web App called "dev"
2. Use the App Service Editor to customize the main home page of the dev web app and add the following code to the body of the page:
```
<h1>This is version 1.0.1 of the web app</h1>
```
3. After you confirm you have two different versions of your Web App running in the prod and dev deployment slots (they have different urls), perform a deployment slot swap in the portal.  Swap using the "dev" site as the source to destination "production". This simulates moving a new version of your app into production
4. Navigate to the production url to confirm the new version of the app is running there

### Lifelines

* [Set up staging environments in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-staged-publishing)

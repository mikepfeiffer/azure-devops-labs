# Lab 10 - Blue-green Deployments with Azure App Service and GitHub

### Application Setup:

1. Create a new public repository in your GitHub account called "MyDemoWebApp" (make sure to add a .gitignore for Visual Studio)
2. Connect to your developer VM via RDP
3. Open a command prompt or terminal and clone the `MyDemoWebApp` repository
4. Run the `dotnet new -i Microsoft.DotNet.Web.ProjectTemplates.2.2::2.2.6` command to install the project template
5. Create a new web app with the `dotnet new webapp -f netcoreapp2.2` command
6. Run the `dotnet dev-certs https --trust` command to enable local SSL support
8. Use the `dotnet build` command to build the application
9. Use the `dotnet run` command to debug the application
10. Use the Git command line to commit your changes and push your code to GitHub

### Deploy a Web App to Azure:

1. Create a new App Service in the Azure Portal (Web App) Make sure to select at least a Standard tier (S1) App Service Plan
2. Navigate to the properties of your Web App > ***Deployment slots*** > and create a deployment slot in your Web App called "dev"
3. Open the resource group for your web app -- you should see two resources...your production web app and the "dev" deployment slot -- click on the "dev" web app
2. In the properties of your "dev" deployment slot, navigate to > ***Deployment Center*** > and configure deployment via GitHub (note: use the App Service build service as your build provider)
3. Visit the url for your "dev" slot web app to see your application live on the internet

### Perform a Zero Downtime Deployment

1. Navigate to the properties of your production Web App in the Azure portal
2. On the main screen, select > ***Deployment slots*** > and the perform a "swap" operation to bring the code in development slot into production

### Validate the Workflow

1. Let's run through the process one more time
2. Update the code in your local project (just add a new message to the "index.cshtml" view in the Pages folder)
3. Commit and push your changes to GitHub (this will trigger a deployment to the "dev" slot)
4. Confirm your changes are live by visiting the "dev" slot url
5. Perform a "swap" to bring your changes into production

### Lifelines

* [Create an ASP.NET Core WebApp](https://docs.microsoft.com/en-us/aspnet/core/getting-started/)

* [Continuous deployment to Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment)

* [Set up staging environments in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-staged-publishing)

### Navigation:

* [Back to Lab Index](https://github.com/mikepfeiffer/azure-devops-labs)
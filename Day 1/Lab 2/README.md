# Lab 2 - Creating Your First Project and Setting up Your Organziation

1. Sign into the Azure DevOps portal (https://dev.azure.com)
2. Give your project a unique name and set the *Visibility* to **private**
3. Navigate to *Organziation Settings* in the Azure DevOps portal (note: you'll need to be viewing the main dashboard where you can see all of your projects)
4. Update your Organization Name to something more meaningful
5. Connect your Azure AD directory instance to your Azure DevOps Organziation in the *Organziation Settings* section.
6. Sign into the Azure AD portal (https://aad.portal.azure.com)
7. Create a new Azure AD user in your directory
8. Head back to dev.azure.com > *Organziation Settings* > *Users* > and add your new Azure AD user and associate the account with the *Project Administrators* group.
9. Click the *Browse extentions* link on the right-hand side of the page to open the Visual Studio Marketplace.
10. Install the "Test & Feedback" extention published by Microsoft.
11. Assign the "Test Manager" extention to the Azure AD user you created in step 7.

### Notes:

Quickstart: Create an organization or project collection
* https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/create-organization

Connect your organization to Azure Active Directory
* https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/connect-organization-to-azure-ad

Add or delete users using Azure Active Directory
* https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-users-azure-active-directory

Quickstart: Install extensions
* https://docs.microsoft.com/en-us/azure/devops/marketplace/install-extension

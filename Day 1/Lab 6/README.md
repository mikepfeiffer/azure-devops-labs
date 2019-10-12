# Lab 6 - Initialize Cloud Shell and Azure DevOps CLI

1. Go to **shell.azure.com** and intitialize your cloud shell instance (select bash, for now, and choose all the defaults)
2. Install the Azure DevOps extention with the `az extension add --name azure-devops` command
3. Create a Personal Access Token for your account at **dev.azure.com**
4. Go back to the cloud shell and sign in with your personal access token using the `az devops login --organization https://dev.azure.com/<YOUR ORG NAME>` command
5. Run the `az repos list` to view a list of your repos
6. Challenge: How can you run the `az repos list` command and get back only the **weburl** for the repo?

### Lifelines:

* [Overview of Azure Cloud Shell](https://docs.microsoft.com/en-us/azure/cloud-shell/overview)

[Get started with Azure DevOps CLI](https://docs.microsoft.com/en-us/azure/devops/cli/get-started)

[Create personal access tokens to authenticate access](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate)

[Sign in with a Personal Access Token (PAT)](https://docs.microsoft.com/en-us/azure/devops/cli/log-in-via-pat)

[Query Azure CLI Command Output](https://docs.microsoft.com/en-us/cli/azure/query-azure-cli)
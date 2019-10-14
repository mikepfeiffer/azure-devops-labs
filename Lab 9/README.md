# Lab 9 - Code Reviews with Git Pull Requests

1. Connect via RDP to your developer VM
2. Navigate to **dev.azure.com** > click on your project > select ***boards*** > and select ***boards*** again
3. Create a ***New item*** in the `ToDo` column
4. Move your work item from the `ToDo` column to the `Doing` column, and from the context menu, create a new branch based on **Master**
5. Open your project in Visual Studio, and from the **Team Explorer**, select the ***Sync*** option and issue a `Pull` operation
6. Navigate to ***Branches*** in **Team Explorer**, and under ***remotes/origin***, right-click and checkout your new branch
7. Modify the code in your `Program.cs` file
8. Issue a commit and push from **Team Explorer**
9. Navigate to **dev.azure.com** and review the repo for your application (make sure your new branch is selected from the drop-down)
10. Click on the link to ***Create a pull request***
11. Fill out a title and description for your pull request
12. Assign the pull request to your Azure AD user account
13. Sign into **dev.azure.com** as your Azure AD user (use an "incognito" mode browser instance) and review and merge the pull request into the **Master** branch

### Lifelines:

* [Review Code with Pull Requests](https://docs.microsoft.com/en-us/azure/devops/repos/git/pull-requests)

* [Pull Request Templates](https://docs.microsoft.com/en-us/azure/devops/repos/git/pull-request-templates)

### Navigation:

* [Back to Lab Index](https://github.com/mikepfeiffer/azure-devops-labs)
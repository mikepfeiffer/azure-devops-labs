# Lab 7 - Getting Started with Git and GitHub

1. Sign up for a free account at **GitHub.com** (use your temp email account)
2. Create a new public repository with a `.gitignore` and open source license
3. Navigate to **github.com/settings/profile** > **Developer Settings** > **Personal Access Tokens**
4. Generate a new personal access token and select all permissions listed under the **repo** scope...make sure you copy the personal access token so you can use it later
5. Navigate back to your GitHub profile and find the repository you created in step two
6. Copy the clone url from the top right-hand side of the repo
7. Connect via RDP to your developer VM and open a **Command Prompt** or **PowerShell** terminal
8. Use the `git clone` command to clone your empty repository
9. Create an HTML file inside the local git repo...add a "hello world" message in the file
10. Use the `git status` to review your untracked changes
11. Use the `git add` command to stage your changes
12. Use the `git commit` to commit your changes to the local repo
13. Use the `git push` command to sync your changes to the GitHub repo (note: this is where you'll need to authenticate with GitHub...you may see a dialog window to login to GitHub, if not, use the command line to enter your GitHub username and your personal access token to auth)
14. Verify you can see your code inside your GitHub repo after push

### Lifelines:

* [Quickstart: Code with Git](https://docs.microsoft.com/en-us/azure/devops/user-guide/code-with-git)

* [Git Reference](https://git-scm.com/docs)
# git/gitworkflow  Create a new repo      Command Line

[git/gitworkflow](https://docs.microsoft.com/en-us/azure/devops/repos/git/gitworkflow?view=azure-devops)


Manage any folder with source code or Visual Studio solution in Git by creating a repo for them. Later you can connect this Git repo to a remote Git repo to share your work with others.

Open up a command prompt and navigate to the top-level folder containing your project's code, or a new folder if you are starting from scratch. Create the Git repository using the init command as shown in the following example. After the repo is created, you'll see a confirmation like Initialized empty Git repository in current directory.

## git init .

[Work in branches](https://docs.microsoft.com/en-us/azure/devops/repos/git/branches?view=azure-devops&tabs=visual-studio) to keep track of your work and [create commits](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits?view=azure-devops&tabs=visual-studio) to snapshot your changes into Git.

Once you are ready to share your code, get the clone URL for the repository you want to connect to and then set up a remote relationship (in this case, origin) so your repo can push changes to a shared repo.

## git remote add origin https://dev.azure.com/fabrikam/Fabrikam/_git/FabrikamFiber

Push your changes to the origin repository to share with others:

## git push origin users/frank/feature



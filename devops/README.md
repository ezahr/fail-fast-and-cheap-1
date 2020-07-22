## https://dev.azure.com/mcc-repo/   projects home 



![hello-azure-again](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/DevOps_maakaf_wat_agile_begon.jpg)

## Clone an existing Git repo
[Clone an existing Git rep](https://docs.microsoft.com/en-us/azure/devops/repos/git/clone?view=azure-devops&tabs=visual-studio)

![createrepo](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/create-a-repo.png)

Create a complete local copy of an existing Git repository by cloning it. 
Cloning a repo downloads all commits and branches in the repo. 
Cloning sets up a named relationship with the existing repo you cloned. 
Use this relationship to interact with the existing repo, 
pushing and pulling changes to share code with your team.

By default, Git assigns the origin to the remote repo you clone from. Most users don't need more than one remote, \
so the tutorial uses origin in its steps. Learn more about setting up remotes to your Git repo.

In this tutorial you learn how to:

    Get the clone URL to your repo
    Clone a repo

Working from the command line? You can view our video tutorial using command line steps on ![Channel9](https://channel9.msdn.com/series/Team-Services-Git-Tutorial/Git-Tutorial-Create-a-repo-from-the-command-line).

## https://dev.azure.com/mcc-repo/
![projectshome](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/dev-azure-com-projects-home-mcc-repo.png)

![clone](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/clone.png)

https://mcc-repo@dev.azure.com/mcc-repo/hello-azure-again/_git/hello-azure-again
username=bosch.peter
password 5vucgwf4lmclizmk7e5fmm535lef5ise6kn2mf5xsph35cnuiuma

````
boscp08@kubernetes-worker2:~/.../virtual-insanity$ git clone https://mcc-repo@dev.azure.com/mcc-repo/hello-azure-again/_git/hello-azure-again 
Cloning into 'hello-azure-again'...
Password for 'https://mcc-repo@dev.azure.com': 5vucgwf4lmclizmk7e5fmm535lef5ise6kn2mf5xsph35cnuiuma
remote: Azure Repos
remote: Found 80 objects to send. (61 ms)
Unpacking objects: 100% (80/80), 839.90 KiB | 3.98 MiB/s, done.
boscp08@kubernetes-worker2:~/.../virtual-insanity$ ls
focal-fossa        ictu-blue            MCC-repo         MSS-nl-covid19-notification-app-backend  nl-covid19-notification-app-design  SocialcoinCity  test-repo.7z  Workbook_Docker_fundamentals
hello-azure-again  Kubernetes_20200612  MCC-repo-backup  mysql                                    OCI                                 test-repo       traefik       Workbook_Docker_fundamentals.7z
boscp08@kubernetes-worker2:~/.../virtual-insanity$ 
````


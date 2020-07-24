
````
$ git checkout master
$ sudo git status
$ git branch new-branch
$ git branch
$ git checkout new-branch
$ sudo git status
$ sudo git push --set-upstream origin new-branche

$ git checkout master
$ sudo git status
$ sudo git merge new-branch
$ sudo git pull
$ sudo git push --set-upstream origin master

$ git branch -d new-branche
$ sudo git push origin --delete new-branch




````



# devops create repo

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git_init.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/create_new_repo.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git_commit.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git_push.png)


|[must-know-commands-to-make-your-first-commit](https://dev.to/juni/git-and-github---must-know-commands-to-make-your-first-commit-333c)
|--------------------------------------|
|sudo rm -rf devops/                                    |
|git clone https://github.com/ezahr/fail-fast-and-cheap/.git|
|sudo git clone https://github.com/ezahr/fail-fast-and-cheap/.git|
||cd ..|
||sudo cp index.nginx-debian.html ./devops|
|cd devops/|
|git status|
|git commit -am "index jeuh"|
|sudo git commit -am "index jeuh"|
|git status|
|sudo git commit -a "index jeuh"|
|sudo git commit -am  "index jeuh"|
|sudo git add .|
|sudo git commit -am  "index jeuh"|
|git status|
|sudo git push|
|history|
|cd /var/www/html/devops/|
|ls|
|nano index.nginx-debian.html |
|sudo nano index.nginx-debian.html |
|git status|
|git add .|
|sudo git add .|
|git status|
|sudo git commit -am "for you devops project"|
|sudo git push|

## create 'feature branche'  from master
![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_00.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_01.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_02.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_03.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_04.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_05.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/it-branche_feature1_06.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/it-branche_feature1_07.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_08.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_09.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_10.png)

![git](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/git-branche_feature1_11.png)

|[branches](https://docs.microsoft.com/en-us/azure/devops/repos/git/branches?view=azure-devops&tabs=command-line#use-branches-to-manage-development)|
|------------------------------------------------------|
|sudo git commit -am "pentested"|
|sudo git checkout master|
|git config --global --edit|
|sudo git checkout feature1| |
|git status|
|clear|
|git status|
|sudo git checkout master|
|sudo git checkout featur|e1 |
|git status|
|sudo git push --set-upstream origin feature1|


## merge 'feature branch' into master

[Git's workflow](https://docs.microsoft.com/en-us/azure/devops/repos/git/pullrequest?view=azure-devops) uses branches to isolate work until you're ready to merge the changes into your default branch, such as master. The pull request is the collaborative process that lets the rest of the team discuss changes in a branch and agree to merge them once everyone approves. Use pull requests to get early feedback from others on work in progress, even if you're not ready to merge the changes into another branch.

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master00.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master01.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master02.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master03.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master04.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master05.png)

![merge](https://github.com/ezahr/fail-fast-and-cheap//blob/master/pictures/merge_feature_branche_into_master06.png)

[apply-changes-from-one-branch-to-another](https://www.jetbrains.com/help/pycharm/apply-changes-from-one-branch-to-another.html?gclid=Cj0KCQjwjer4BRCZARIsABK4QeVp50Oynvq_9kHTnyT9VkzgFQwRHjhSf9QMmiZAoR-xlBG63GkFyCkaArOFEALw_wcB#cherry-pick)




# ...develop some code...  sudo git checkout master -> sudo git merge feature1 ->  sudo git pull ->  sudo git push

|sudo git checkout master|
|sudo git merge feature1|
|git status|
|sudo git status|
|sudo git push|
|sudo git push --set-upstream origin master|
|git status|
|git pull|
|sudo git pull|
|cat index.nginx-debian.html |
|sudo git push|



````
ubuntu@ubuntu:/var/www/html/devops$ sudo git pull
remote: Enumerating objects: 61, done.
remote: Counting objects: 100% (61/61), done.
remote: Compressing objects: 100% (57/57), done.
remote: Total 59 (delta 14), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (59/59), 4.19 MiB | 3.95 MiB/s, done.
From https://github.com/ezahr/fail-fast-and-cheap/
   9b200ad..ed1848e  master     -> origin/master
Merge made by the 'recursive' strategy.
 README.md                            |  90 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 pictures/README.md                   |   1 +
 pictures/create_new_repo.png         | Bin 0 -> 204118 bytes
 pictures/git-branche_feature1_00.png | Bin 0 -> 143121 bytes
 pictures/git-branche_feature1_01.png | Bin 0 -> 134851 bytes
 pictures/git-branche_feature1_02.png | Bin 0 -> 312707 bytes
 pictures/git-branche_feature1_03.png | Bin 0 -> 113205 bytes
 pictures/git-branche_feature1_04.png | Bin 0 -> 42419 bytes
 pictures/git-branche_feature1_05.png | Bin 0 -> 77962 bytes
 pictures/git-branche_feature1_06.png | Bin 0 -> 355992 bytes
 pictures/git-branche_feature1_07.png | Bin 0 -> 149919 bytes
 pictures/git-branche_feature1_08.png | Bin 0 -> 187574 bytes
 pictures/git-branche_feature1_09.png | Bin 0 -> 86942 bytes
 pictures/git-branche_feature1_10.png | Bin 0 -> 327600 bytes
 pictures/git-branche_feature1_11.png | Bin 0 -> 323409 bytes
 pictures/git_commit.png              | Bin 0 -> 212788 bytes
 pictures/git_init.png                | Bin 0 -> 1692313 bytes
 pictures/git_push.png                | Bin 0 -> 154407 bytes
 18 files changed, 90 insertions(+), 1 deletion(-)
 create mode 100644 pictures/README.md
 create mode 100644 pictures/create_new_repo.png
 create mode 100644 pictures/git-branche_feature1_00.png
 create mode 100644 pictures/git-branche_feature1_01.png
 create mode 100644 pictures/git-branche_feature1_02.png
 create mode 100644 pictures/git-branche_feature1_03.png
 create mode 100644 pictures/git-branche_feature1_04.png
 create mode 100644 pictures/git-branche_feature1_05.png
 create mode 100644 pictures/git-branche_feature1_06.png
 create mode 100644 pictures/git-branche_feature1_07.png
 create mode 100644 pictures/git-branche_feature1_08.png
 create mode 100644 pictures/git-branche_feature1_09.png
 create mode 100644 pictures/git-branche_feature1_10.png
 create mode 100644 pictures/git-branche_feature1_11.png
 create mode 100644 pictures/git_commit.png
 create mode 100644 pictures/git_init.png
 create mode 100644 pictures/git_push.png
ubuntu@ubuntu:/var/www/html/devops$ ;s
-bash: syntax error near unexpected token `;'
ubuntu@ubuntu:/var/www/html/devops$ ls
README.md  index.nginx-debian.html  pictures
ubuntu@ubuntu:/var/www/html/devops$ cat index.nginx-debian.html 
<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
<style>
    body {
        width: 35em;
        margin: 0 auto;
        font-family: Tahoma, Verdana, Arial, sans-serif;
    }
</style>
</head>
<body>
<h1>Welcome to nginx!</h1>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required for your devops project feature1 pentested.</p>

<p>For online documentation and support please refer to
<a href="http://nginx.org/">nginx.org</a>.<br/>
Commercial support is available at
<a href="http://nginx.com/">nginx.com</a>.</p>

<p><em>Thank you for using nginx.</em></p>
</body>
</html>
ubuntu@ubuntu:/var/www/html/devops$ sudo git push
Username for 'https://github.com': ezahr
Password for 'https://ezahr@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 373 bytes | 373.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/ezahr/fail-fast-and-cheap/.git
   ed1848e..7b3d81f  master -> master



````

[How to Delete a Git Branch Both Locally and Remotely](https://www.freecodecamp.org/news/how-to-delete-a-git-branch-both-locally-and-remotely/)

// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName


git fetch -p







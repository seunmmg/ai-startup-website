# Collaborative Website Development with Git and Github

1. ## Install git

Go to git website and download it or download it using the url: https://git-scm.com/downloads

## Create a Github repository

![](./img/1.Create%20a%20Github%20acc.png)

## Clone repository

Open your github click your repository and copy the url code 

![](./img/2.Clone%20repo.png)

open terminal create a folder name git-project the clone your repositrory with the command git clone url

![](./img/3.Git%20clone2.png)

## git branch for tom
To check the newly created branch for Tom named update-navigation

![](./img/4.Git%20branch.png)

## git status 
To check the file index.html that is to be committed.

![](./img/5.Git%20status.png)

## git add index.html
index.html file is ready to be committed

![](./img/6.Git%20add.png)

## Git commit and Git push
git commit is used to commit the file index.html and git push is to push it to online repo

![](./img/7.Git%20commit%20and%20push.png)

## git pull
 After we switch to main branch with the command git checkout, we pull the changes tom made in update-navigation to main branch

![](./img/8.Git%20pull.png)

## git branch for jerry
This command creates jerry branch: git checkout -b add-contact-info

git add index.html - shows the stages jerry made to index.html file

git commit -m "Add contact information" - saves jerrys changes in the branch history with a message

git push origin add-contact-info - This uploads jerry's branch to github


# Merging Changes

## Switch to branch

On github, switch to the branch Tom has been working on which is update-navigation.

![](./img/10.%20Tom%20branch.png)

## Create a new pull request

Click "This branch is 2 commits behind" to initiate a pull request. 

![](./img/11.Create%20pull%20request%201.png)

This will take you to a new page which will allow you to create a pull request. 

![](./img/12.%20Create%20pull%20request%202.png)

After reviewing Tom's work and everything looks good, click create pull request again. Create a title and description.

![](./img/13.%20create%20pull%20request%204.png)

## Steps to update Jerry's branch
open terminal, run git checkout add-contact-info to switch to jerry's branch then git pull origin main to pull latest changes from main branch.

![](./img/14.git%20check%20and%20pull.png)

## Finalizing Jerry's work

Git push origin add-contact-info to push the changes to github 

![](./img/15.%20git%20push.png)

## conflict resolution 
conflict encountered and resolved.

![](./img/16.conflict%20encountered.png)

![](./img/17.conflict%20resloved.png)

## Successful Merge of PRs

![](./img/18.successful%20merge%20of%20prs.png)
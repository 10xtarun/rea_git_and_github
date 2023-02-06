# Git And GitHub
> A quick guide and cheatsheet for Git and GitHub.
---
## Step-by-step commands for Git
```
git init
```
> This will initialize a project folder with empty git repository.
---
```
git config user.name <your_github_username>
git config user.email <your_email_id>
```
> This two commands will set you username and email_id into the repo config/settings, globally on your local. This will attached in commits and other information.
---
```
git config --local user.name <your_github_username>
git config --local user.email <your_email_id>
```
> This is same as previous command but sets the user information only in the current repo / folder.
---
```
git add .
```
> This will add all the new, modified and deleted files to git. Also called as staging of the changes made till now before commiting.
---
```
git add <file_name>
```
> This will stage specific files for the provided filename.
---
```
git commit -m "<your_commit_message>"
```
> This will commit your code for the staged files, note providing a commit message is required.
---
```
git log
```
> This will return a list of commits made earlier (includes yours and other teams commits if made).In the output list you can observe, properties of a commit, which are as:
1. commit id or hash - unique string for each and every commit
2. time & date - when was the commit done
3. author - username or email of the person who has done the commit
4. message - commit message provided when commit was done
---
```
git status
```
> Status will show you list of files modified, new ones and deleted ones
---
```
git branch
```
> Lists all the branches available in your repo and also displays the current branch you are in.
---
```
git checkout <branch_name>
```
> Switches from current branch to the other branch.
---
```
git checkout -b <branch_name>
```
> This will create a new branch with the name provided and switches into it at the same time.
---
```
git remote set-url origin <your_repo_url>
```
> This will set remote repo URL with the origin to your local repo. Remote repos can be on GitHub,BitBucket, CodeCommit, etc.
---
```
git push -u origin <local_branch_name>
```
> If you have created a new branch on your local repo and you need to push the branch remote then use this command to push your branch for the very first time.
---
```
git push
```
> This will push the changes comitted in your branch in your local repo to remote repo.
---
```
git pull
```
> This will pull the changes (if any) from remote repo to the branch in local repo.
---
```
git pull <branch_name>
```
> This will pull the changes from the branch specified into your branch.
---
```
git fetch --all
```
> This will fetch all the exisiting branches in remote repo to your local repo.
---


## Step-by-step setup for GitHub
1. Sign-in to your GitHub account.
2. Go to create new repository.
3. Add the details like, repo name and description, keep the repo public as of now.
4. Once you have created the GitHub repo you will find 2 options.
> 1. create repo from scratch  on local and add the remote repo
> 2. or your repo is already exisitng on local and just need to add the remote repo
5. you can select whatever you like, if selected 2 option then go with "add remote origin" command
6. start with pull push activity.
---
## Authentication for Git and GitHub
> You will need a authentication token for push and other commands from your local git to remote git, here steps to generate token is provided:
1. Go to settings page of GitHub account.
2. Click on developer settngs and options to generate tokens will be displayed.
3. You need to select generate "Personal Access Token" (PAT) "classic".
5. Give suitable name, select expiry date and tick the repo related options.
6. Click on generate token and you will displayed with a token and you can copy it only once.
7. Copy it and store the PAT somewhere safely.
8. So whenver you are pushing from terminal you will be 

> Thank You!
---

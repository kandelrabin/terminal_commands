# Terminal and Git Commands


## Terminal Commands
> List of useful **terminal** commands for macOS. Further commands can be found [here](https://ss64.com/mac/).

|Command|Action|
|:----    | :----|
|`/`|Root directory|
|`~`|Home directory (`user_name` folder)|
|`.`|Current directory|
|`pwd`|Present working directory|
|`ls`|List files in the current working directory <br> *Flags*: <br>`-a` List all files including hidden files/folders <br> `-l` List all files including details|
|`cd <directory>`|Change the current working directory <br> *Additional use cases*:<br>`cd -` Go to last opened directory <br> `cd ..` Go one level up in the directory|
|`mkdir <directory>` |Make a directory|
|`rm <directory>`|Remove a directory <br> *Flags*: <br> `-r` Recursively remove the directory including subdirectories <br> `-f` Forced deletion without asking for confirmation|
|`mv <filename> <destination>` |Move a file/folder to a destination folder|
|`cp <filename> <destination>`|Copy a file to a destination folder <br> *Flags*: <br> `-r` Recursively copy files (including subdirectories) to destination folder|
|`touch <filename.ext>`|Create a file with a specified extension|
|`open <filename>`|Open a file|


## Git Commands
> List of useful comands for **Git** version control. Further commands can be found [here](https://git-scm.com/docs).

❗️Remember following: 

- Always run `git` commands from the directory that has been initialized. 
- On terminal this is marked as `git:(main)`

|Command|Action|
|:----    | :----|
|`git init`|Initialize a git repository on the current working directory|
|`git status`|Check status of files tracking|
|`git add`|Add files to a staging area|
|`git commit -m "message"`|Commit files from staging area to the git repository|
|`git log`|Show a log of all commits <br> To exit press  `q`|
|`git revert <commit hash> -m "message"`|Revert changes of specified commit, and creates a new commit with a message|
|`git reset --hard`|Reset current branch to a previous commit, discards all local changes to files|
|`git remote add origin git@github.com:<your_github_name>/<your_repo>.git`|Add a new remote origin to your local Git repository <br> ✅ **SSH** has URL format:`git@github.com:<your_github_name>/<your_repo>.git` <br> ❌ **HTML** has URL format:`https://github.com/<github_username>/<your_repo>.git`|
|`git branch -M main`| Rename the current branch to `main`|
|`git push -u origin main`|Push the changes from local `main` branch to the remote repository|
|`git clone <repo ssh url>`|Clone a repository into a new directory|
|`git pull`|Fetch changes from a remote repository into the current branch|
|`git branch`|List all existing branch; current branch is highlighted in green|
|`git branch <feature_name>`| Create new branch|
|`git checkout <feature_name>`| Switch to newly created branch|
|`git branch -d <feature_name>`| Delete the branch|

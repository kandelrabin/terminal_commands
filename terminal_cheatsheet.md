# Terminal and Git Commands


## Terminal Commands
> List of useful **terminal** commands for mac OS.

|Command|Action|
|:----    | :----|
|`/`|Root directory|
|`~`|Home directory (user_name folder)|
|`.`|Current directory|
|`pwd`|Present working directory|
|`ls`|List files in the current working directory <br> *Flags*: <br> <code style="color : blue">-a</code> List all files including hidden files/folders <br> <code style="color : blue">-l</code> Go back to last opened directory|
|`cd`<code style="color : blue">\<directory\></code>|Change the current working directory <br> *Additional use cases*:<br> <code style="color : blue">cd -</code> Go to last opened directory <br> <code style="color : blue">cd ..</code> Go one level up in the directory|
|`mkdir` <code style="color : blue">\<directory\></code>|Make a directory|
|`rm`<code style="color : blue">\<directory\></code>|Remove a directory <br> *Flags*: <br> <code style="color : blue">-r</code> Recursively remove the directory including subdirectories <br> <code style="color : blue">-f</code> Forced deletion without asking for confirmation|
|`mv`<code style="color : blue">\<filename\> \<destination\></code> |Move a file/folder to a destination folder|
|`cp`<code style="color : blue">\<filename\> \<destination\></code>|Copy a file to a destination folder <br> *Flags*: <br> <code style="color : blue">-r</code> Recursively copy files (including subdirectories) to destination folder|
|`touch` <code style="color : blue">\<filename.ext\></code>|Create a file with a specified extension|
|`open`<code style="color : blue">\<filename\></code>|Open a file|


## Git Commands
> List of useful comands for **Git** version control.

Remember following:

- Always run `git` commands from the directory that has been initialized. 
- On terminal this is marked as **<code style="color : blue">git:(</code><code style="color : red">main</code><code style="color : blue">)</code>**.

|Command|Action|
|:----    | :----|
|`git init`|Initialize a git repository on the current working directory|
|`git status`|Check status of files tracking|
|`git add`|Add files to a staging area|
|`git commit -m`<code style="color : blue">\"message\"</code>|Commit files from staging area to the git repository|
|`git log`|Shows a log of all commits <br> To exit press  <code style="color : blue">q</code>|
|`git revert`<code style="color : blue">\<commit hash\></code>|Revert changes of specified commit, and creates a new commit|
|`git revert`<code style="color : blue">\<commit hash\></code> `-m` <code style="color : blue">\"message\"</code>|Revert changes of specified commit, and creates a new commit with a message|
|`git reset --hard`|Reset current branch to a previous commit, discards all local changes to files|



















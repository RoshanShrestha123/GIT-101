# GIT 101 🚀

## How do i know if **GIT** is already setup on my machine?

Simple! type `git -v` or `git --version` on CMD (command prompt) if you are using windows,
or use terminal if you are using Mac/Linux.
Also, if you are using mac or linux, most probably git is installed by default.

#### ❌ I don't have GIT on my machine.
- Go to this Official website: https://git-scm.com/ , download the git based on your system and follow the simple installation process. (Just Next, Next, Next, Next & Boom. You have git on your machine now.)
- If you are confuse on how to install the git on your machine, [Try this for windows](https://www.javatpoint.com/how-to-install-git-on-windows), [Try this for Mac](https://phoenixnap.com/kb/install-git-on-mac), & [Try this for Linux](https://www.tutorialspoint.com/how-to-install-git-on-linux).
- [_For windows user_], Use **Git Bash** instead of CMD, which will be installed automatically after the setup.

#### ✅ I have GIT on my machine.
Configure git with your name & email. Copy &  following command on your terminal/gitbash/cmd & provide your name & email at a time. 

```js 
git config --global user.name "type-your-name"
```
```js 
git config --global user.email "type-your-email"
```
Now you are successfully configure the git with your name & email, you can verify once with this command: `git config --list`

Want to edit the config, try this command: `git config --global --edit`
  
#### [Advance configuration, totally optional]
```js
git config --global core.editor "your-editor-command"
```

 This command will set your default commit editor to your fav editor. Default should be `vim` you can replace it with `nano` or `code`.
```js
git config --global core.autocrlf true
``` 
You can set the Line Ending to autocrlf=true to handle the inconsistencies if your team will be working on different OS.


## Now we are ready to use the git 🙌

### Basic git commands 🍀
|Command|Description|
|---|----|
|`git init` | Type this inside any folder, this will initialize the git on that particular folder.
|`git add <file-name>`|Git will start tracking that file changes |
|`git add .`|if you want to add all the file at once|
|`git commit -m "message"`| Adding the commit message to the file added|
|`git status`| Check the status of what file is being added or committed|
|`git log`|This is showcase the history of all the committed message, when & by whom|


### Working with branches commands 🍀
|Command|Description|
|---|----|
|`git branch <branch-name>`| Create new branch |
|`git checkout <branch-name>`| Switch to already created branch|
|`git checkout -b <branch-name>`|Create branch & Switch with single command|
|`git merge <source-branch>`| This will merge source branch to the currently active branch |




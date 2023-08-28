# GIT 101

### How do i know if **GIT** is already setup on my machine?

Simple! type `git -v` or `git --version` on CMD (command prompt) if you are using windows,
or use terminal if you are using Mac/Linux.
Also, if you are using mac or linux, most probably git is installed by default.

#### ❌ I don't have GIT on my machine.
- Go to this Official website: https://git-scm.com/ , download the git based on your system and follow the simple installation process. (Just Next, Next, Next, Next & Boom. You have git on your machine now.)
- If you are confuse on how to install the git on your machine, [Try this for windows](https://www.javatpoint.com/how-to-install-git-on-windows), [Try this for Mac](https://phoenixnap.com/kb/install-git-on-mac), & [Try this for Linux](https://www.tutorialspoint.com/how-to-install-git-on-linux).
- [_For windows user_], Use **Git Bash** instead of CMD, which will be installed automatically after the setup.

#### ✅ I have GIT on my machine.
- Configure git with your name & email. Copy &  following command on your terminal/gitbash/cmd & provide your name & email at a time. 
- ```git config --global user.name "type-your-name"```
- ```git config --global user.email "type-your-email"```
- Now you are successfully configure the git with your name & email, you can verify once with this command: `git config --list`
  
#### [Advance configuration, totally optional]
- ```git config --global core.editor "your-editor-command"``` This command will set your default commit editor to your fav editor. Default should be `vim` you can replace it with `nano` or `code`.
- ```git config --global core.autocrlf true``` . You can set the Line Ending to autocrlf=true to handle the inconsistencies if your team will be working on different OS.






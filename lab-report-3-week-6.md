# Week 6 Lab Report: Streamlining `ssh` Configuration
[February 11, 2022]

## Table of Contents:
1. Creating/Opening and Editing `.ssh/config`
2. `ssh` Login To Account After 
3. `scp` Command To Account After

**1. Creating/Opening and Editing `.ssh/config`**

Opening `ssh` and creating `.ssh/config`:
![Image](Images3/creatingConfig.png)
I first attempted to open `.ssh/config` but realized I do not have the file, but only the directory. Therefore I changed my directory to `ssh` in my terminal and created the config file by using the `touch` command. 

Opening newly created `.ssh/config`:
![Image](Images3/creatingConfig2.png)
Then I opened the empty file using the `open` command in terminal to ensure that the file has been successfully created.

Editing `.ssh/config`:
![Image](Images3/editingConfig.png)
After ensuring the file was created, I started editing the file by adding the following text
```
Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lwi22aef
```
Then I saved the file and closed it returning to my terminal.

**2. `ssh` Login To Account After**
![Image](Images3/sshSuccess.png)
After editing the file, I ensured that it works by using the command `ssh ieng6` to login to my remote account. As shown in the screenshot, the command worked meaning the file editing was successful.

**3. `scp` Command To Account After**
![Image](Images3/scpSuccess.png) 
To ensure that the this streamline works for other commands not just `ssh`, I tried `scp WhereAmI.java` just like in our first lab to ensure that it works. As seen in the screenshot, the file `WhereAmI.java` successfully copied over to the remote computer, therefore showing this works.
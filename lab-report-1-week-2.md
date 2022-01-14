# Week 2 Lab Report: Remote Access
[January 14, 2022]

## Table of Contents:
1. Installing VS Code
2. Remotely Connecting
3. Trying Some Commands
4. Moving Files with `scp`
5. Setting an SSH Key
6. Optimizing Remote Running

**1. Installing VS Code**

*Note*: If VS Code is already installed on your computer, you can skip to step 2 (Remotely Connecting).

1.1 Open the Visual Studio Code website and follow the instructions to download Visual Studio Code for your computer.
![Image](Images/vscode.png)

1.2 After installing Visual Studio Code, the following window should open when you open the application:
![Image](Images/vscodeOpen.png)

**2. Remotely Connecting**

2.1 Look up course-specific account for CSE15L in this link [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

2.2 Open Terminal in VS Code by clicking on Terminal in the control bar and selecting "New Terminal"
![Image](Images/vscodeNewTerminal.png)

2.3 Type the following command into the terminal replacing "zz" with  course-specific account letters:

`ssh cs15lwi22zz@ieng66.ucsd.edu`

2.4 When logging in for the first time, the following message appears. Type yes and press enter.
![Image](Images/firstLogin.png)

2.5 Type password and press enter and the following results:
![Image](Images/loginResults.png)

**3. Trying Some Commands**

3.1 Run a few commands both on your computer and on the remote computer

*Own Computer*:
![Image](Images/cdCommands.png)
--cd changes the directory
![Image](Images/lsCommands.png)
--ls lists the files, l means long-listing, a lists hidden files, and t shows the last edited time

*Remote Computer*
![Image](Images/remoteComputerCommands.png)
--cp copies, cat reads files, can only been
![Image](Images/exitCommand.png)
--exit or Ctrl-D exits the remote control
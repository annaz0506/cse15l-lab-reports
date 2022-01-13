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

1.2 After installing Visual Studio Code, the following window should open:
![Image](Images/vscodeOpen.png)

**2. Remotely Connecting**

2.1 Look up your course-specific account for CSE15L in this link [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

2.2 Open Terminal in VS Code by clicking on Terminal in the control bar and selecting "New Terminal"
![Image](Images/vscodeNewTerminal.png)

2.3 Type the following command into the terminal replacing "zz" with your course-specific account letters:
`ssh cs15lwi22zz@ieng66.ucsd.edu`

*Note*: after 15 is a lowercase L, not 1
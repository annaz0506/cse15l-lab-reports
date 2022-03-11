# Week 10 Lab Report: Commonmark & Markdown Parse
[March 11, 2022]

## Table of Contents:
1. How to find tests with different results
2. First Test Correctness and Changes
3. Second Test Correctness and Changes

**1. How to find tests with different results**

Firstly I ran the command `time bash script.sh > labResults.txt` in the shared file for the class and then the same command for my group's file but changed `labResults.txt` to `labResults2.txt`.
![Image](Images5/classResults.png)
![Image](Images5/groupResults.png)
Then I moved both of the files to the same directory and used the command `diff labResults.txt labResult2.txt` to find generate a list of the results that were different for each tester.
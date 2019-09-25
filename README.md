# Homework 0: Getting Started
Due: 	Sunday, 29 September, 10pm

Note: you won't be penalized if you are still having software install issues. We just need to know by 30 September if you are so that we can help.

## Overview
This assignment consists of eight parts. None of them are hard, but some of them will take a while to download and configure software, so leave enough time. We are doing things to get started for the course, motivate the problems we will be solving in the class, and make sure that you have the proper software tools installed for the remainder of the course.

We would like you to complete this assignment by the second lecture, and that is the due date. If you have barriers in your critical path that are keeping you from doing part or all of this assignment – e.g., waiting for an external hard drive to arrive – please contact the instructors, who will work with you to figure out an alternative deadline. Note, however, that the sooner you get this setup done, the less behind you will get.

## What to hand in via Canvas & Github Classroom
1. Attach a single document (PDF preferred), containing
  * A screenshot of running your edited hw0.py (part 6)
  * Text you write for parts 7 and 8, in hw0.txt 
2. Complete the survey on Canvas (see link in part 2)
3. You will also turn in hw0.py

## Part 1: Join the 310 Slack Workspace
We ask that you contribute questions, comments, and thoughts relating to the class on the HCDE310 Slack workspace. Visit [this link to join the workspace](https://join.slack.com/t/hcde310a19/shared_invite/enQtNzY4NzY2MjY4MDg1LTdhOTlhNGVjMjg0YWIwYTg4M2RkYjI1OWFiNWI0ZTEwMDZkNzA5ZmZmNWEyM2QzMTFlMTdkNTcwNzdjMTljOTY).

Posts made to the group are only visible to members of the workspace - students enrolled in the class and the instructors. In future assignments, we will write software to process records of activity on the workspace. We hope that the workspace will allow for more interactive and informal collaboration. This group is the place to post questions and requests for help. See the syllabus for details about the collaboration policy, which is quite liberal.

You also message us there. We recommend that you create a message thread with all five instructors (Sean, Raina, Steven, Jaesuk, and Melody) and yourself and use that for any private messages with the instruction team. For now, you can just say hi, but later that will be a place where we can all help you. Having each of us on the thread also means that if the last instructor who helped is offline when you are stuck, someone else can jump in, see the whole history, and help out.

## Part 2: Complete a background survey (if you haven’t already)
One of the great things about HCDE is that students come from a variety of backgrounds and bring a mix of expertise and interests. This can, however, make pacing the course a bit of a challenge. To help us pace the course this quarter, please [complete this survey](https://canvas.uw.edu/courses/1321165/quizzes/1162607).

## Part 3: Get your tools set up
If you have not already done any Python development on your computer, you will need to do some work to get Python installed and to select a development environment. To do so, [follow the software setup instructions on Canvas](https://canvas.uw.edu/courses/1321165/pages/software-setup).

## Part 4: Learn to use a terminal window
 To get started, we'll be using terminal to run our first Python programs this quarter. Terminal is an app that lets you type commands (at the command line or command prompt). This can be frustrating at first, as you need to remember or be able to look up what command to use. However, it can be much more expressive and flexible than a graphical interface, because the vocabulary of possible commands is much greater than can be shown in a graphical interface.

On your computer, open a terminal window and try out some different commands. For an overview, here are some tutorials for each operating system:
* MacOS
  * [Apple documentation](https://developer.apple.com/library/content/documentation/OpenSource/Conceptual/ShellScripting/CommandLInePrimer/CommandLine.html)
  * [iMore's overview](https://www.imore.com/how-use-terminal-mac-when-you-have-no-idea-where-start)
  * [TeamTreehouse intro](http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line)
* Windows
  * Windows 10 supports both Powershell and Windows Command Prompt. We recommend using Powershell, but both will get the job done.
  * [PowerShell Beginner's Guide](https://github.com/PowerShell/PowerShell/blob/master/docs/learning-powershell/powershell-beginners-guide.md)
  * [Princeton's Command Prompt intro](http://www.cs.princeton.edu/courses/archive/spr05/cos126/cmd-prompt.html)

## Part 5: Get started with git, and download the starter homework code.
We'll be using Github Classroom to distribute and turn in homeworks. [Instructions on how to get started are here](https://canvas.uw.edu/courses/1321165/pages/getting-started-with-github-classroom), but if you are viewing these instructions, you have already gotten started.

Once you have a git account setup, please go back to Slack and send the instructors a message. That will let us match your account to who you are, and we can then add you to the private LectureCode and Solutions repositories. 

## Part 6: Learn to use your development environment
You can use any number of development environments to work with Python. For HCDE 310, we'll provide instructions using PyCharm. If you want a little more guidance or for your examples to look like what we use in class, we recommend you also use PyCharm. We have, though, also provided a list of our favorites on Canvas.

Open hw0.py in your development environment. Edit it according to the comments in the file. Run it and take a screenshot of the output.

To take a screenshot:
*	in Windows: alt+PrintScreen (while running Player)
*	in OS X: the Grab utility or Command-Shift-4 (see [this guide](http://guides.macrumors.com/Taking_Screenshots_in_Mac_OS_X)). Or you can take a screenshot of the entire screen using Command-Shift-3.

## Part 7: Design a program
The purpose of this exercise is to get you familiar with issues in data manipulation and to get you thinking about how a computer might do it. For this exercise, write an English description (not a computer program!) of instructions for counting the number of words in a document (we've provided hw0.txt as a starter). Try to be as precise as possible and remove all ambiguity. It may help you to eliminate ambiguity if you anticipate that the person to whom you are giving the instructions will purposely try to misinterpret your instructions so as to get the wrong result.

You may be asked to team up and compare your approach with a classmate’s in the next section, so please be prepared to share.

## Part 8: Reflection
Was the previous exercise easy or hard for you? What was satisfying or unsatisfying about trying to describe the instructions in English?

Also, it would help us if you would take a few sentences tell us what you want to get out of the course. Thanks!

## Finally, turn hw0 in.
For this assignment, please turn in your homework on Canvas and on Github Classroom. Once we're sure that Github classroom works for our needs, we'll switch to using mostly that, but Canvas gives you a backup to show that you had your homework turned in.

To turn it in on Canvas, visit the course page, click on assignments, find hw0, and upload hw0.py, hw0.txt, and your screenshot.

To turn it in on Github Classroom, open Terminal (if on Mac) or Powershell (if on Windows) and navigate to the location of the repo (the HW0 folder you downloaded). To upload your changes,
1. type `git add .` and press enter to register the changes you've made. This tells git to track all of the files in the directory.
2. Then, type `git commit -m "<your message here>"` and press enter. The message should describe the changes you've made. F
3. Finally, type `git push` and hit enter to upload your homework.

You can visit Github on the web to verify that the files match what you think they should. 

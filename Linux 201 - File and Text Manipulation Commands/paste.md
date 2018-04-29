https://www.theurbanpenguin.com/linux-paste-command/

Using the Linux Paste Command Effectively

Linux Paste Command

The Linux Professional Institute LPIC-1 101 exam requires that you have a knowledge of a number of commands that can be used to manage text files. One such command is the Linux paste command. I know that this is something that many Instructor struggle with especially when trying to come up with ideas of how the command is used. The Linux paste command is quite simple really, it takes two or more files and combines their data. Line 1 of both file1 and file2 will appear together in the new file as line 1.

I am Lost Already
Ok, I can tell I have you confused already, so let’s take a look at two files and use the paste command to join them. The first file is called users with the following three lines:

    bob
    joe
    bill
The second file contains department names and is called departments :

    sales
    IT
    kitchen
Using the Linux paste command we can join these two files together:

$ paste users departments
The resulting output will look like this:

    bob sales
    joe IT
    bill kitchen
Create the files and try it running the command on your system.

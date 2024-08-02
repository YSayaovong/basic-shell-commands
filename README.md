# basic-shell-commands

The purpose of this lab project is to become more comfortable with the shell and shell commands. It consists of the following five parts:

PART 1: Experiment with some basic shell commands.

Open a terminal window on your Linux virtual machine.
Notice the shell prompt components: user@hostname:dir$
Use the pwd command to identify your location.
Use the cd / command to get to the root of your directory tree structure.
Use the cd ~  command to get back to your user's home directory.
Take a screenshot (filename: screenshot_1) of the above activities.
Clear the shell with the clear command.
PART 2: Learn about commands to get help.

Use the man ls command to review the ls command. Type q to quit.
Use the info ls command to review the ls command. Take note of how this is different from the man command. Type q to quit.
Use the help command to find out more information about itself by typing in help help
Take a screenshot (filename: screenshot_2) of the above activities.
Clear the shell with the clear command.
PART 3: Learn about commands to navigate the directory tree structure while creating files and directories.

While in your user's home directory, use the ls –l /  command to view the contents of the / directory.
Take a mental note of which directories are part of the Linux Filesystem Hierarchy Standard (FHS) and those that are not (refer back to the learning materials for this module).
Use the mkdir test1 command to add a new directory in your home directory.
Use the cd command to change into the test1 directory that you just created in the previous step.
Use touch file1 to create a new empty file in the test1 directory.
Use the ls command with a single option (flag) to view the details of file1. (If you can't remember which option is used to view the details, what can you do to view the available options for that command?)
Use rm file1 to delete it.
Exit the test1 directory and return to its parent directory.
Use rmdir test1 to delete it.
Use the mkdir command to add a directory named test2 in your home directory.
Copy the /etc/passwd file to the ~/test2 directory so a copy of /etc/passwd is stored at ~/test2/passwd.bak
Use one command to verify that the copy of /etc/passwd was successfully made to ~/test2/passwd.bak while also indicating that it is not empty. The output of this command must consist of only two short lines.
Take a screenshot (filename: screenshot_3) of the above activities.
Clear the shell with the clear command.
PART 4: Learn about commands used to view the contents of files.

Use the cat command to review the contents of the ~/test2/passwd.bak
Take a screenshot (filename: screenshot_4) of the above activity.
Clear the shell with the clear command.
Resize your terminal window to make it half of the height that it was before by dragging the bottom of the window up.
Now try step 1 again, but use the less command instead of cat. (Use the up and down arrow keys to scroll through the file, type in q, to exit less.)
Return your terminal window to its previous height by dragging the bottom of the window down.
Now try step 1 again, but use the head command instead of cat.
Now try step 1 again, but use the tail command instead of cat.
Try steps 7 and 8 again, but add the -n2 option/flag to the head and tail commands and see what happens.
Type cat > file1 and enter a single sentence about how you feel about Linux. Hit Enter and then type CTRL + d to exit.
Type cat file1 to view its contents.
Create another file with this command ls -la ~ > file50
Append to the end of file50 the contents of ~/test2/passwd.bak using this command cat ~/test2/passwd.bak >> file50
Review the final contents of file50 your work using the less command. You should remember how to exit less.
Search file50 for any lines with the word root by using this command: grep root file50
Take a screenshot (filename: screenshot_5) of the above activities.
Clear the shell with the clear command.
PART 5: Try out some new commands!

w
who
whoami
cal
date
date +%Y
let linuxage=$(date +%Y)-1991
echo 'Linux is' $linuxage 'years old!' > birthday
cat birthday
cat birthday | wc
env | grep PATH
groups
id
uname -a
hostname
shutdown (before entering this command, be prepared to type in the next command very quickly afterward - within 60 seconds!)
shutdown -c
Take a screenshot (filename: screenshot_6) of the above activities.
After taking this screenshot, if you are unsure what the previous commands are used for based on their output, go back and review the man page for the ones you are unsure about. 

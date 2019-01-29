0x00. Shell, basics

0-current_working_directory
Prints the absolute path name of the current working directory

1-listit
Displays the contents list of the current directory

2-bring_me_home
Shell script that changes the working directory to the user's home directory

3-listfiles
Displays current directory contents in a long format

4-listmorefiles
Displays current directory contens, including hidden files (starting with .) in long format.

5-listfilesdigitonly
Displays current directory conents.
	- ong format
	- with user and group IDs displayed numerically
	- and hidden files (starting with .)

6-firstdirectory
Script to create directory "holberton" in /tmp folder

7-movethatfile
Moves file "Betty" from /tmp/ to /tmp/holberton

8-firstdelete
Deletes file "Betty" in /tmp/holberton

9-firstdirdeletion
Deletes folber "Holberton" in /tmp/

10-back
Changes the working directory to the previous one

11-lists
Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type
Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

13-symbolic_link
Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

14-copy_html
Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
All HTML files are considered to have the extension .html

15-lets_move
Creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
Assumed that the directory /tmp/u will exist when we will run your script

16-clean_emacs
Creates a script that deletes all files in the current working directory that end with the character ~.

17-tree
Creates a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory.
Only allowed to use two spaces in your script, not more.

18-commas
Command that lists all the files and directories of the current directory, separated by commas (,).
	- Directory names should end with a slash (/)
	- Files and directories starting with a dot (.) should be listed
	- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
	- Only digits and letters are used to sort; Digits should come first
	- You can assume that all the files we will test with will have at least one letter or one digit
	- The listing should end with a new line



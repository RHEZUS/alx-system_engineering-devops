# Project 0x00. Shell Basics

This project was carried out during my fullstack software engeneering training at [ALX Africa](https://www.alxafrica.com/) and aims to practive the basic commands related to the navigation snd file management in shell.

## Technologies

- Script written in bash
- Tested on Ubuntu 20.4

## Files

Each of the following line is a shell script file except school.mgc.

| FILE | DESCRIPTION |
| ----------- | ----------- |
| [`0-current_working_directory`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/0-current_working_directory) | Prints the absolute path name of the current working directory |
| [`1-listit`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/1-listit) | Display the contents list of your current directory. |
| [`2-bring_me_home`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/2-bring_me_home) | Changes the working directory to the user’s home directory without using any shell variables. |
| [`3-listfiles`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/3-listfiles) |  Display current directory contents in a long format. |
| [`4-listmorefiles`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/4-listmorefiles) | Display current directory contents, including hidden files (starting with .). Use the long format. |
| [`5-listfilesdigitonly`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/5-listfilesdigitonly) |Display current directory contents in long format with user and group IDs displayed numerically And hidden files (starting with .). |
| [`6-firstdirectory`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/6-firstdirectory) | Creates a directory named *my_first_directory* in the */tmp/directory*. |
| [`7-movethatfile`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/7-movethatfile) | Move the file *betty* from */tmp/* to */tmp/my_first_directory*. |
| [`8-firstdelete`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/8-firstdelete) | Delete the file *betty* which is in */tmp/my_first_directory* |
| [`9-firstdirdeletion`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/9-firstdirdeletion) | Delete the directory *my_first_directory* that is in the */tmp* directory. |
| [`10-back`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/10-back) | Changes the working directory to the previous one. |
| [`11-lists`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/11-lists) | Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the */boot* directory (in this order), in long format. |
| [`12-file_type`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/12-file_type) | prints the type of the file named iamafile. The file *iamafile* will be in the */tmp* directory when we will run your script. |
| [`13-symbolic_link`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/13-symbolic_link) | Create a symbolic link to */bin/ls*, named *__ls__*. The symbolic link should be created in the current working directory. |
| [`14-copy_html`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/14-copy_html) | Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. considering HTML files have the extension .html |
| [`100-lets_move`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/100-lets_move) |  moves all files beginning with an uppercase letter to the directory */tmp/u*. Assuming that the directory */tmp/u* will exist when we will run your script |
| [`101-clean_emacs`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/101-clean_emacs) | Create a script that deletes all files in the current working directory that end with the character `~`. |
| [`102-tree`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/102-tree) | creates the directories *welcome/*, *welcome/to/ and welcome/to/school* in the current directory. You are only allowed to use two spaces (and lines) in your script, not more. |
| [`103-commas`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/103-commas) | lists all the files and directories of the current directory, separated by commas (,).
- The file should end with a (`/`). 
- Files startin with a `.` should slso be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line |
| [`school.mgc`](https://github.com/RHEZUS/alx-system_engineering-devops/blob/master/0x00-shell_basics/school.mgc) |school.mgc is a magic file that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. |



# 0x02. Shell, I/O Redirection, and filter project

The project 0x02. Shell, I/O Redirection, and filter is the third project carried out to learn Shell. The project aimed to implement what we had learned about filtering information and redirecting the input and outputs of the different commands. some of the commands we used in this project are (find, head, tail, wc, sort uniq...) which are very helpful when it comes to filtering files and their content.

## Technologies

- Script written in bash
- Tested on Ubuntu 20.4

## Files
These files represent the different script files of the project and the description shows what the script does.

| FILES | DESCRIPTION |
| ----------- | ----------- |
|[`0-hello_world`](0x02-shell_redirections/0-hello_world) | Print “Hello, World”, followed by a new line to the standard output. |
|[`1-confused_smiley`](0x02-shell_redirections/1-confused_smiley) | Display a confused smiley "(Ôo)'. |
|[`2-hellofile`](0x02-shell_redirections/2-hellofile) | Display the content of the */etc/passwd* file. |
|[`3-twofiles`](0x02-shell_redirections/3-twofiles) | Display the content of /etc/passwd and */etc/hosts* |
|[`4-lastlines`](0x02-shell_redirections/4-lastlines) | Display the last 10 lines of */etc/passwd* |
|[`5-firstlines`](0x02-shell_redirections/5-firstlines) | Display the first 10 lines of */etc/passwd*  |
|[`6-third_line`](0x02-shell_redirections/6-third_line) | Display the third line of the file *iacta* that is in the current directory without using the command `sed` |
|[`7-file`](0x02-shell_redirections/7-file) | Create a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending with a new line. |
|[`8-cwd_state`](0x02-shell_redirections/8-cwd_state) | Write into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it. |
|[`9-duplicate_last_line`](0x02-shell_redirections/9-duplicate_last_line) | Duplicate the last line of the file *iacta* |
|[`10-no_more_js`](0x02-shell_redirections/10-no_more_js) | Delete all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders |
|[`11-directories`](0x02-shell_redirections/11-directories) | counts the number of directories and sub-directories in the current directory including hidden directories. |
|[`12-newest_files`](0x02-shell_redirections/12-newest_files) |  Display the 10 newest files in the current directory.  |
|[`13-unique`](0x02-shell_redirections/13-unique) | Take a list of words as input and print only words that appear exactly once.  words should be sorted |
|[`14-findthatword`](0x02-shell_redirections/14-findthatword) | Display lines containing the pattern “root” from the file /etc/passwd |
|[`15-countthatword`](0x02-shell_redirections/15-countthatword) | Display the number of lines that contain the pattern “bin” in the file /etc/passwd |
|[`16-whatsnext`](0x02-shell_redirections/16-whatsnext) | Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd. |
|[`17-hidethisword`](0x02-shell_redirections/17-hidethisword) | Display all the lines in the file /etc/passwd that do not contain the pattern “bin”. |
|[`18-letteronly`](0x02-shell_redirections/18-letteronly) | Display all lines of the file /etc/ssh/sshd_config starting with a letter including capital letters. |
|[`19-AZ`](0x02-shell_redirections/19-AZ) | Replace all characters A and c from input to Z and e respectively. |
|[`20-hiago`](0x02-shell_redirections/20-hiago) | Create a script that removes all letters c and C from input. |
|[`21-reverse`](0x02-shell_redirections/21-reverse) | Write a script that reverse its input. |
|[`22-users_and_homes`](0x02-shell_redirections/22-users_and_homes) | Display all users and their home directories, based on the */etc/passwd* sorted by users. |
|[`100-empty_casks`](0x02-shell_redirections/100-empty_casks) |  Find all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path), Hidden files should be listed, One file name per line You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep` |
|[`101-gifs`](0x02-shell_redirections/101-gifs) | List all the files with a .gif extension in the current directory and all its sub-directories. Hidden files should be listed, Only regular files (not directories) should be listed, The names of the files should be displayed without their extensions, The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay), One file name per line, The listing should end with a new line, You are not allowed to use basename, grep, egrep, fgrep or rgrep |
|[`102-acrostic`](0x02-shell_redirections/102-acrostic) | An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.  Create a script that decodes acrostics that use the first letter of each line. The ‘decoded’ message has to end with a new line. You are not allowed to use grep, egrep, fgrep or rgrep |
|[`103-the_biggest_fan`](0x02-shell_redirections/103-the_biggest_fan) | Write a script that parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Order by number of requests, most active host or IP at the top. You are not allowed to use grep, egrep, fgrep or rgrep |

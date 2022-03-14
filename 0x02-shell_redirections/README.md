file 0 prints “Hello, World”, followed by a new line to the standard output.

file 1 displays a confused smiley "(Ôo)'.

file 2 displays the content of the /etc/passwd file.

file 3 displays the content of /etc/passwd and /etc/hosts

file 4 displays the last 10 lines of /etc/passwd

file 5 displays the first 10 lines of /etc/passwd

file 6 displays the third line of the file iacta.

file 7 creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

file 8 writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

file 9 duplicates the last line of the file iacta

file 10 deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

file 11 counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted

file 12 displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest

file 13 takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted

file 14 displays lines containing the pattern “root” from the file /etc/passwd

file 15 displays the number of lines that contain the pattern “bin” in the file /etc/passwd

file 16 displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

file 17 displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.

file 18 displays all lines of the file /etc/ssh/sshd_config starting with a letter.

include capital letters as well

file 19 replaces all characters A and c from input to Z and e respectively.

file 20 removes all letters c and C from input.

file 21 reverses its input.

file 22 displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file

file 23  finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep

file 24 lists all the files with a .gif extension in the current directory and all its sub-directories.

Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep

file 25 decodes acrostics that use the first letter of each line.

An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval.
The ‘decoded’ message has to end with a new line
You are not allowed to use grep, egrep, fgrep or rgrep

file 26 parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep

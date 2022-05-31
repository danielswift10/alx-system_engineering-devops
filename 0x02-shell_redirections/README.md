# SHELL REDIRECTION TASK

0-#!/bin/bash

echo "Hello, World": This script *prints `“Hello, World”`, followed by a new line to the standard output*

1-#!/bin/bash

echo "\"(Ôo)'": This script *displays a confused smiley `"(Ôo)'`.*

2- #!/bin/bash

cat /etc/passwd: This script *displays the content of the `/etc/passwd` file.*

3-#!/bin/bash

cat /etc/passwd /etc/hosts: This script *displays the content of `/etc/passwd` and `/etc/hosts`*

4-#!/bin/bash

tail -n 10 /etc/passwd: This script *displays the last 10 lines of `/etc/passwd`*

5-#!/bin/bash

head -n 10 /etc/passwd: This script *displays the first 10 lines of `/etc/passwd`*

6-#!/bin/bash

head -n 3 iacta | tail -n 1: This script *displays the third line of the file `iacta.` The file `iacta` will be in the working directory

7-#!/bin/bash

echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\): This script *creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text Best School ending by a new line.*

8-#!/bin/bash

ls -la > ls_cwd_content: This script *writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.*

9-#!/bin/bash

tail -n 1 iacta >> iacta: This script *duplicates the last line of the file `iacta`. The file `iacta` will be in the working directory*

10-#!/bin/bash

find . -type f -name "*.js" -delete: This script *deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.*

11-#!/bin/bash

find . -type d -not -name '.' | wc -l: This script *counts the number of directories and sub-directories in the current directory.*

12-#!/bin/bash

ls -t1 | head -n 10: This script *displays the 10 newest files in the current directory.*

13-#!/bin/bash

sort | uniq -u: This script  *takes a list of words as input and prints only words that appear exactly once.*

14-#!/bin/bash

grep -i "root" /etc/passwd: This script *displays lines containing the pattern “root” from the `file /etc/passwd1`*

15-#!/bin/bash

grep -c -i "bin" /etc/passwd: This script *displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`*

16-#!/bin/bash

grep -i "root" -A 3 /etc/passwd: This script *displays lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`*

17-#!/bin/bash

grep -i -v "bin" /etc/passwd: This script *displays all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.*

18-#!/bin/bash

grep -i "^[a-z]" /etc/ssh/sshd_config: This script *displays all lines of the file `/etc/ssh/sshd_config` starting with a letter*

19-#!/bin/bash

tr "A" "Z" | tr "c" "e": This script *replaces all characters `A` and `c` from input to `Z` and `e` respectively.*

20-#!/bin/bash

tr -d "cC": This script *removes all letters `c` and `C` from input.*

21-#!/bin/bash

rev: This script *reverse its input.*

22-#!/bin/bash

cut -d ':' -f 1,6 /etc/passwd | sort: This script *displays all users and their home directories, sorted by users. based on the the `/etc/passwd file`*

23-#!/bin/bash

find . -empty | rev | cut -d '/' -f 1 | rev: This script *finds all empty files and directories in the current directory and all sub-directories.*

24-#!/bin/bash

find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f: This script *lists all the files with a `.gif` extension in the current directory and all its sub-directories.*

25-#!/bin/bash

cut -c 1 | paste -s -d '': This script *decodes acrostics that use the first letter of each line.*

26-#!/bin/bash

tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev: This script *parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.*





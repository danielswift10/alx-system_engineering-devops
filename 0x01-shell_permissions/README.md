## SHELL PERMISSION TASKS

0-**#!/bin/bash**

**su betty**: This script *switches the current user to the user `betty`.*

1-**#!/bin/bash** 

**id -un**: This script *prints the effective username of the current user.*

2- **#!/bin/bash**

**id -Gn**: This script *prints all the groups the current user is part of.*

3-**#!/bin/bash**

**chown betty hello**: This script *changes the owner of the file `hello` to the user `betty`.*

4-**#!/bin/bash**

**touch hello**: This script *creates an empty file called `hello`.*

5-**#!/bin/bash**

**chmod u+x hello**: This script *adds execute permission to the owner of the file `hello`.*

6-**#!/bin/bash**

**chmod ug+x,o+r hello**: This script *adds execute permission to the owner and the group owner, and read permission to the users, to the file `hello`.*

7-**#!/bin/bash**

**chmod ugo+x hello**: This script *adds execution permission to the owner, the group owner and the other users, to the file `hello`.*

8-**#!/bin/bash**

**chmod 007 hello**: This script *sets the permission to the file `hello` as no permission at all to owner, no permission at all to group, and all permissions to the other users*

9-**#!/bin/bash**

**chmod 753 hello**: This script *sets the mode of the file `hello` to that.*

10-**#!/bin/bash**

**chmod --reference=olleh hello**: This script *sets the mode of the file `hello` the same as `olleh`'s mode.*

11-**#!/bin/bash**

__chmod a+X *__: This scipt *adds execute permissions to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.*

12-**#!/bin/bash**

**mkdir -m 751 my_dir**: This script *creates a directory called `my_dir` with permissions 751 in the working directory.*

13-**#!/bin/bash**

**chgrp school hello**: This script *changes the group owner to `school` for the file `hello`.*

14-**#!/bin/bash**

__chown vincent:staff *__: This script *changes the owner to `vincent` and the group to `staff` for all the files and directores in the working directory.*

15-**#!/bin/bash**

**chown -h vincent:staff _hello**: This script *changes the owner and the group owner to `_hello` to `vincent` and `staff` respectively.*

16-**#!/bin/bash**

**chown --from=guillaume betty hello**: This script *changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`*

17-**#!/bin/bash**

**telnet towel.blinkenlights.nl**: This script *will play the StarWars IV episode in the terminal*

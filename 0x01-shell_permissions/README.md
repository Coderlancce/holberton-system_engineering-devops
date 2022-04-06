# Shell, permissions


More commands in the Shell

| Command | What that do? |
| ------------- | ------------- |
| su  | Switches the current user |
| id -un  | Prints the effective username of the current user |
| groups | Prints all the groups the current user is part of |
| sudo chown | Changes the owner of the file |
| touch | Create empty file |
| chmod u+x | Adds execute permission to the owner of the file |
| chmod ug+x,o+r | Adds execute permission to the owner and the group owner, and read permission to other users |
| chmod ugo+x | Adds execution permission to the owner, the group owner and the other users |
| chmod 007 | That sets the permission, Owner: no permission at all, Group: no permission at all, Other users: all the permissions |
| chmod 753 | Give this permissions "-rwxr-x-wx" |

Soon more info and outputs
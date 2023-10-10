0. Switches the current user to the user betty: "su betty".
1. prints the effective username of the current user: "whoami".
2. prints all the groups the current user is part of: "groups".
3. script that changes the owner of the file hello to the user betty: "chown betty hello".
4. creates an empty file called hello: "chmod 744 hello".
5. adds execute permission to the owner of the file hello: "chmod 744 hello".
6. adds execute permission to the owner and the group owner, and read permission to other users, to the file hello: "chmod 754 hello".
7. adds execution permission to the owner, the group owner and the other users, to the file hello: "chmod a+x hello".
8. sets the permission to the file hello as follows: "chmod 007 hello".
9. sets the mode of the file hello to this: "chmod 753 hello".
10. sets the mode of the file hello the same as olleh’s mode: "chmod --reference=olleh hello".
11. all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed: "chmod -R a+X .".
12. directory called my_dir with permissions 751 in the working directory: "mkdir -m 751 my_dir".
13.  changes the group owner to school for the file hello: "chgrp school hello".
14. owner to vincent and the group owner to staff for all the files and directories in the working directory: "chown -R vincent:staff .".
15. the owner and the group owner of _hello to vincent and staff respectively: "chown -h vincent:staff _hello"
16. the owner of the file hello to vincent only if it is owned by the user guillaume: "chown --from=guillaume vincent hello".

This is a repo for all shell permissions 

1. 0. My name is Betty   " su betty"   a script that switches the current user to the user betty.
2. 1. Who am I    "whoami"  script that prints the effective username of the current user. 
3. 2. Groups  "groups"  script that prints all the groups the current user is part of.
4. 3. New owner "chown betty hello" script that changes the owner of the file hello to the user betty.
4. 4. Empty!  "touch hello"  script that creates an empty file called hello.
5. 5. Execute  "chmod u+x hello" script that adds execute permission to the owner of the file hello.
6. 6. Multiple permissions "chmod ug+x,o+r hello"  script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7. 7. Everybody!  "chmod ugo+x hello"  script that adds execution permission to the owner, the group owner and the other users, to the file hello.
8. 8. James Bond  "chmod 007 hello"   a script that sets the permission to the file hello as follows: Owner: no permission at all --Group: no permission at all --Other users: all the permissions.
9. 9. John Doe "chmod 753 hello"  script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.
10. 10. Look in the mirror    "chmod --reference=olleh hello"   script that sets the mode of the file hello the same as olleh’s mode.
11. 11. Directories  "sudo chmod -R +111 */" script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12. 12. More directories  "mkdir -m 751 my_dir"   script that creates a directory called my_dir with permissions 751 in the working directory.
13. 13. Change group "chgrp school hello"  a script that changes the group owner to school for the file hello.
14. 14. Owner and group " chown vincent:staff *"  script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. 15. Symbolic links  "chown -h vincent:staff _hello"   script that changes the owner and the group owner of _hello to vincent and staff respectively.
16. 16. If only   "chown --from=guillaume betty hello"   script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

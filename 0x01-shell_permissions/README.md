su betty - This will switch the current user to another user called 'betty'

whoami - This prints the username of the current user that is logged into the machine

group - This will list all the groups the current user belongs to

chown betty hello - Changes the ownership of the file 'hello' to the user called 'betty'

touch hello - This creates a file with name 'hello'

chmod 744 hello - This will add execute permission to the owner of the file 'hello'

chmod 754 hello - This gives execute permission to owner and group owner and read permission to other users to the file 'hello'

chmod ugo+x hello - This gives execute permission to all the groups

chmod 007 hello - Owner and group users have no permission, but all permissions (read, write and execute) is given to the user

chmod 753 hello - This grant the user all permission, the user group, read and execute permission only, and other user write and execute permission

chmod --reference=olleh hello - This set the mode of two files as the same. 

find . -type d -exec chmod a+x -- {} +\ - Add execusion permission to all folder and subfolder excluding the files. 

mkdir -m 751 my_dir - This create a file with the permission: read, write and execute for the owner. read and execute for the group and execute permission for the others.

chgrp school hello - This changes the group ownership of the file 'hello' to the username 'bello'

chown vincent:staff _hello - This will change the ownership of files in a directory to vincent and staff

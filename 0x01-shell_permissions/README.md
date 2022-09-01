su betty - This will switch the current user to another user called 'betty'

whoami - This prints the username of the current user that is logged into the machine

>>> Task 2

chown betty hello - Changes the ownership of the file 'hello' to the user called 'betty'

touch hello - This creates a file with name 'hello'

chmod 744 hello - This will add execute permission to the owner of the file 'hello'

chmod 754 hello - This gives execute permission to owner and group owner and read permission to other users to the file 'hello'

chmod ugo+x hello - This gives execute permission to all the groups

chmod 007 hello - Owner and group users have no permission, but all permissions (read, write and execute) is given to the user

chmod 753 hello - This grant the user all permission, the user group, read and execute permission only, and other user write and execute permission

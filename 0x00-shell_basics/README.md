#!/bin/bash

pwd "\n" >>> This print the working directory and put the cursor on the next line for the shell prompt to take commands.

ls  >>> This will list the content of the current directory and the cursor after the directory.

cd ~ >>> Changes working  directory to the HOME directory
ls -l >>> This will display the current directory in a long format
ls -al >>> This displays the hidden files in the current directory
ls -na >>> Display current durrent directory in long format, user and group IDS displayed numerically and hidden files starting with .
mkdir /tmp/my_first_directory >>> This create a director called my_first_directory in the /tm/ directory
mv /tmp/betty /tmp/my_first_directory >>> This move a file name betty in /tmp directory to a sub-directory in /tmp parent directory
rm /tmp/my_first_directory/betty >>> This will delete the file name betty in the sub-directory "my_first_directory", which is in the directory /tmp.
rmdir /tmp/my_first_directory/ >>> This will delete the directory "my_first_directory" in /tmp directory
cd - >>> This will take you to the previous directory you worked on
ls -al . .. /boot >>> This will display all the files and hidden ones in long format in the current directory, parent of current directory and the boot directory
file /tmp/iamafile >>> this will display the type the file belongs to  
ln -s /bin/ls _ls_ >>> This create a soft link between /bin/ls and _ls_. This makes _ls_ like a shortcut to /bin/ls
cp -u *.HTML . .. >>> This will copy file from the current directory, the file  with .htm, that are  newer file or does not exist in the parent folder
cp -r [[:upper:]]* /tmp/u >>> This will copy all files starting with uppercase to /tmp/u
rm ~* . >>> This will delete all file that ends with the tilda sign

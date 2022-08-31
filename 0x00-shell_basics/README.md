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

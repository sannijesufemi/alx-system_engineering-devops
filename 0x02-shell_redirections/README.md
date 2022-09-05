>> Description of shell script used to perform task <<

echo "Hello, World" - This will print the statement in the quote to the standard output stream

echo "\"(Ôo)'" - This will print the text within the quote - confused smiley

cat /etc/passwd - This will display the content of the /passw/  which is a file in the /etc/ directory

cat /etc/passwd /etc/hosts - This print the contents of two files; passwd and hosts of the etc directory

tail -n 10 /etc/passwd - This will display the last ten lines of the content of the file passwd in the /etc directory

head -n 10 /etc/passwd - This will display the first ten lines of the content of the file passwd in the /etc directory

cat iacta | Head -3 | Tail -1 - This will display the third line of the content of the file iacta

Task 7

ls -la > ls_cwd_content - This saves and write the content of the current working directory to the file ls_cwd_content

tail -n 1 iacta > iacta - This duplicate the last line of the iacta file

find . -name "*.js" -type f -delete - This deletes all the file with the extension .js in the parent directory and the subdirectories

find . -mindepth 1 -type d | wc -l - This will count the number of directories within  a current directory and exclude the current directory from the count

sort | uniq -u - THis displays list of word that only appear ones

grep 'root' /etc/passwd - This search through the content of the passwd file and display lines where ther word 'root' appears

grep -c 'bin' /etc/passwd - This display the number of lines the word 'bin' appears in the file passwd.

grep -A 3 'bin' /etc/passwd - This display three lines after the ecountering a line with the word 'bin'

grep -v 'root' /etc/passwd - This display lines of text that has no word 'bin' in them

grep '^[[:upper:]]\|^[[:lower:]]' /etc/ssh/sshd_config - THis display lines of text That begins with alphets only; capital or small letter.

tr Ac Zc - This will replace all character 'A' and 'c' from the user input with 'Z' and 'c'

tr -d Cc - This will remove both upper and lower case 'C' from user's input

rev - THis reverse the text from users

cut -d':' -f1,6 /etc/passwd |sort - This displays all users and their home directories sorted by users with columns 

find . -empty -printf '%f\n' - The search through the current direct direct, sub directories and files for empty files and directories. It prints out the empty files and directories out one item on a single line.

find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f - This list all files with .gif extension in the current directory and in all its subdirectories in a sorted order

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

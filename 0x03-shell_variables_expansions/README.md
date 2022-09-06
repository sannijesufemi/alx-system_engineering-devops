>>>>>>> SHELL VARIABLES EXPANSIONS

alias ls="rm *" - This changes the delete all files command to ls. Anytime the command ls is pressed, all files will be deleted in the current working directory

echo "Hello $USER" - This display the word Hello and the name of the currently logged in user.

export PATH=${PATH}:/action - This display the current path and affix it with the content ':' and the directory path '/action.

echo $PATH | tr ":" "\n" | wc -l - This display the number of PATHS within a directory on the next line.

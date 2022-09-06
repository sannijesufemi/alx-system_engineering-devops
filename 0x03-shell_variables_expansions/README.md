>>>>>>> SHELL VARIABLES EXPANSIONS

alias ls="rm *" - This changes the delete all files command to ls. Anytime the command ls is pressed, all files will be deleted in the current working directory

echo "Hello $USER" - This display the word Hello and the name of the currently logged in user.

export PATH=${PATH}:/action - This display the current path and affix it with the content ':' and the directory path '/action.

echo $PATH | tr ":" "\n" | wc -l - This display the number of PATHS within a directory on the next line.

printenv - This display all the global/environment variables

set - This display all local variables and environment variables, and functions

BEST="School" - This will create a variable with the name 'BEST' and store the value 'School' in it...

export BEST="School" - This export a Global variable with the variable name 'BEST' and assign it with te value 'School'

echo $(($TRUEKNOWLEDGE +128) - This add the value 128 with an environment variable TRUEKNOWLEDGE, and print it out.

echo $(($POWER / $DIVIDE)) - This compute the division of two en vironm ent variables 'POWER' and 'DIVIDE' respectively, and display the result

echo $((BREATH**LOVE)) -This raise an environment variable BREATH to the power of another environment variable LOVE. It computes the exponential and print the result.

echo $((2#$BINARY)) - This conver the environment variable BINARY with a value in binary number system to the decimal number system.

echo {a..z}{a..z} | tr ' ' '\n' | grep -v 'oo' - This print out all the possible combinations of two lower case letters together on a newline and excluding the letter 'oo' out of the list .






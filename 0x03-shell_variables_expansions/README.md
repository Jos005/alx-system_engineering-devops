#0x03. Shell, init files, variables and expansions
This file contains list of scripts and what each does.

Task 0. alias ls="rm *" - create alias of ls set to rm *

Task 1. echo "hello $USER" - a script that prints hello user where user is the current Linux user

Task 2. PATH=$PATH:/action - Add /action to the PATH

Task 3. echo $((`echo $PATH | grep -o ":/" | wc -1`+ 1))

Task 4. printenv -  lists environment variables

Task 5. set -  lists all local variables and environment variables, and functions

Task 6. BEST="School" - creates a new local variable with name BEST and value School

Task 7. export BEST="School" - creates a new global variable with name BEST and value School

Task 8. echo $((128 + $TRUEKNOWLEDGE)) - prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE

Task 9. echo $(($POWER/$DIVIDE)) - prints the result of POWER divided by DIVIDE (both are environment variables)

Task 10. echo echo $((BREATH**LOVE)) - displays the result of BREATH to the power LOVE (both are environment variables)  

Task 11. echo $((2#$BINARY)) -converts a number from base 2 to base 10, base 2 is stored in the environment variable BINARY

Task 12. echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" - prints all possible combinations of two letters, except oo

Task 13. printf '%.2f\n' $NUM - prints a number with two decimal places, followed by a new line

Task 14. printf "%x\n" $DECIMAL - converts a number from base 10 to base 16 (number in base 10 is stored in environment variable DECIMAL)

Task 15. tr 'A-Za-z' 'N-ZA-Mn-za-m'- encodes and decodes text using the rot13 encryption. Assume ASCII

Task 16. paste - - | cut -f1 - prints every other line from the input, starting with the first line.

Task 17. printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 bestchol - adds the two numbers stored in the environment variables WATER and STIR and prints the result


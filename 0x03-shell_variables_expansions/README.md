# 0x03. Shell, init files, variables and expansions

##  commands

- alias ls="rm *"
create alias .

- echo "hello $USER"
say hallo to user.
- export PATH=$PATH:/action
The path to success is to take massive, determined action

-echo $((`echo $PATH | grep -o ":/" | wc -l` + 1))
count number of dirs in PATH
- printenv
print global variables .

- set
Create a script that lists all local variables and environment variables, and functions.

- BEST="School"
create a local variable called BEST .
-export BEST="School"
create a global variable called BEST .

- echo $(($TRUEKNOWLEDGE + 128))
add value in TRUEKNOWLEDGE variable  to 128  .
- echo $(($POWER/$DIVIDE))
display result of divide power var on divide var .
- echo $(($BREATH**LOVE))
display result of var BREATH in power of  LOVE var .

- echo "$((2#$BINARY))"
converts a number from base 2 to base 10.

- echo {a..z}{a..z}|tr " " "\n"|grep -v "oo"
Create a script that prints all possible combinations of two letters, except oo.
- printf "%.2f" $NUM | sort
prints a number with two decimal places, followed by a new line.
- echo '%x\n'$DECIMAL
 converts a number from base 10 to base 16.
 
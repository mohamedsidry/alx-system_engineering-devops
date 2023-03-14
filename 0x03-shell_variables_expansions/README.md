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

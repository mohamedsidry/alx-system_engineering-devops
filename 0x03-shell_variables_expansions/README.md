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
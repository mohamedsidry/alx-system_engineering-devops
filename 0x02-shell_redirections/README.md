# COMMAND DESCRIPTION

-[x] echo "Hello ,World"
display hello world in terminal .
-[] echo "\"(Ôo)'"
backslash ignore the character after from interprated as special character.
-[x] cat /etc/passwd
display content of passwd file .
-[x] cat /etc/passwd /etc/hosts
display content of passwd and hosts files .
-[x] cat /etc/passwd | tail -n 10
display the last 10 lines of passwd file .
-[x] cat /etc/passwd | head
display the first 10 lines of file.
-[0] head -3 iacta | tail -n 1
display the 3rd line in iacta file.
-[x] ls -la > ls_cwd_content
overwrite command to file.
-[x] tail -n 1 iacta >> iacta
duplicate the last line of file.
-[x] find . -type f -name "*.js" -delete
delete all regular js files .
-[x] find . -type d -not -name '.' | wc -l
count all dirs and subdir of working dir .
-[x] ls -f1 | head -n 10
display the newest 10 file in working dir .
-[x] sort | uniq -u
uniq and soted .
-[X] cat /etc/passwd | grep root
display lines cntaining root .
-[x] cat /etc/passwd | grep bin | wc -l
diplay number of lines containing the word bin .
-[x] grep -i "root" -A 3 /etc/passwd
what is next .
-[x] grep -v "root" /etc/passwd
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
-[x] grep -i '^[a-z]' /etc/ssh/sshd_config
letters only please
-[x] tr "A" "Z" |tr "c" "e"
translate A to Z and c to e

-[] tr -d "Cc"
delete C and c


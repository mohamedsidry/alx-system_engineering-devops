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

-[x] tr -d "Cc"
delete C and c

-[x] rev
reverse input

-[x] cut -d ":" -f 1,6 /etc/passwd | sort
display all users and there home dirs sorted by users

## ADVANCED Tasks

-[x] find -empty | rev | cut -d "/" -f 1 | rev
find empty files/dirs reverse cut from '/' and reverse again

- [x] find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d "." -f 2- | rev |LC_ALL=C sort -f
find all regulat gif files

- [x] cut -c 1 | paste -s -d ''
Acrostic : first letter is the key .

- [] tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev
woooooow i like it 
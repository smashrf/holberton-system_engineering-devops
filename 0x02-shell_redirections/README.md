**README**
I/O, Redirections and filters.
Hello, world: echo "Hello, World"
Confused smiley : "\"(Ôo)'"
Hello file : cat /etc/passwd
Two files : cat /etc/passwd /etc/host
Last lines : tail /etc/passwd
First lines : head /etc/passwd
Third line : head -n 3 iaca | tail -n 1
File stranger name : echo "Holberton School" > \*\\'\''"Holberton School"\'\''\\*$\?\*\*\*\*\*:)
State repository : ls -la > ls_cwd_content
Repeat the last line: tail -n 1 iacta >> iacta
Recursive Deletion : find . -name *.js -type f -delete
Directories : find ./* -type d | wc -l
Newest list : ls -t | head -n 11
Unique word : sort $1 | uniq -u
Grep : grep -w /etc/passwd -e 'root'
Count words : grep -w /etc/passwd -e "bin"| wc -w
Show lines after match : grep -A 3 /etc/passwd -e 'root' | cat
Hidden lines : grep -v "bin" /etc/passwd
Letter only : grep /etc/ssh/sshd_config -e '^[A-Za-z]'
Change letter : tr A Z | tr c e
Delete words : tr -d C | tr -d c
Reverse : rev

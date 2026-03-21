# linux
## command
1. cd (change directory)
- cd ..  ->   parent directory
- cd /   ->   root
- cd ~   ->   home 
- cd -   ->   previous
***
2. ls (list)
- ls -l   ->  show detiles
- ls -a   ->  show hidden files
***
3. cat (concatenate file and print output)
- cat -v   ->  show hidden character
***
4. chmod (change read,write,execute for each group)
- chmod +x  ->  user can execute
***
5. grep (find part of name in file/directory)
***
6. run python/bash(./file)
***

## tips
1. mail ->  echo $MAIL or env | grep -i "mail"
- under /var/mail/
2. shell ->  echo $SHELL or cat /etc/passwd | grep "user"
- under /bin/bash
3. index(inode) number  ->  ls -i or stat
- under /bin/bash
3. network interface  -> ip a

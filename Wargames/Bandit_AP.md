<pre>
0 -> 1:    cat readme
1 -> 2:    cat "./-"
2 -> 3:    cat "./spaces in this filename"
3 -> 4:    cat inhere/.hidden
4 -> 5:    file inhere/*
           cat inhere/-file07
5 -> 6:    find inhere/ ! -executable -size 1033c -readable
           cat inhere/maybehere07/.file2
6 -> 7:    find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
           cat /var/lib/dpkg/info/bandit7.password
7 -> 8:    grep 'millionth' data.txt
8 -> 9:    cat data.txt | sort | uniq -u
9 -> 10:   strings data.txt | grep '='
10 -> 11:  cat data.txt | base64 -d
11 -> 12:  cat data.txt
           https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,13)&input=R3VyIGNuZmZqYmVxIHZmIFdJQU9PU0Z6TWpYWEJDMEtvU0tCYko4cHVRbTVsSUVp
12 -> 13:  mkdir -p /tmp/xcn
           cd /tmp/xcn && cat ~/data.txt | xxd -r > data
           file data
           mv data data.gz && gunzip data.gz
           file data
           mv data data.bz2 && bunzip2 data.bz2
           file data
           mv data data.gz && gunzip data.gz
           file data
           mv data data.tar && tar xf data.tar
           ls
           file data5.bin
           mv data5.bin data5.tar && tar xf data5.tar
           ls
           file data6.bin
           mv data6.bin data6.bz2 && bunzip2 data6.bz2
           file data6
           mv data6 data6.tar && tar xf data6.tar
           ls
           file data8.bin
           mv data8.bin data8.gz && gunzip data8.gz
           ls
           file data8
           cat data8
13 -> 14:  ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
14 -> 15:  echo 'fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq' | nc -v 127.0.0.1 30000
15 -> 16:  openssl s_client -connect 127.0.0.1:30001
16 -> 17:  nmap -sT -p 31000-32000 127.0.0.1
           for i in {31046,31518,31691,31790,31960}; do openssl s_client -connect 127.0.0.1:$i; done;
           openssl s_client -connect 127.0.0.1:31790
17 -> 18:  diff passwords.new passwords.old
18 -> 19:  ssh bandit18@bandit.labs.overthewire.org -p 2220 'cat readme'
19 -> 20:  ./bandit20-do id
           ls -al /etc/bandit_pass
           ./bandit20-do cat /etc/bandit_pass/bandit20
20 -> 21:  echo 'VxCazJaVykI6W36BkBU0mJTCM8rR95XT' | nc -lp 4444 &
           ./suconnect 4444
21 -> 22:  ls -al /etc/cron.d
           cat /etc/cron.d/cronjob_bandit22
           cat /usr/bin/cronjob_bandit22.sh
           cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
22 -> 23:  ls -al /etc/cron.d
           cat /etc/cron.d/cronjob_bandit23
           cat /usr/bin/cronjob_bandit23.sh
           echo I am user bandit23 | md5sum | cut -d ' ' -f 1
           cat /tmp/8ca319486bfbbc3663ea0fbe81326349
23 -> 24:  ls -al /etc/cron.d
           cat /etc/cron.d/cronjob_bandit23
           cat /usr/bin/cronjob_bandit23.sh
           mkdir -p /tmp/bandit23
           chmod o+w /tmp/bandit23
           ---
           [Create a bash file, and put in contents, set +x]:
           #!/bin/bash
           cat /etc/bandit_pass/bandit24 > /tmp/bandit23/bandit24
           ---
           cp 24 /var/spool/bandit24/foo/
           cat /tmp/bandit23/bandit24
24 -> 25:  



</pre>

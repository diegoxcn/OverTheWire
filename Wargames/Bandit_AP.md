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
18 -> 19:  



</pre>

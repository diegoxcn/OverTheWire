<pre>
0 -> 1:    cat readme <br>
1 -> 2:    cat "./-" <br>
2 -> 3:    cat "./spaces in this filename" <br>
3 -> 4:    cat inhere/.hidden <br>
4 -> 5:    file inhere/* <br>
           cat inhere/-file07 <br>
5 -> 6:    find inhere/ ! -executable -size 1033c -readable <br>
           cat inhere/maybehere07/.file2 <br>
6 -> 7:    find / -user bandit7 -group bandit6 -size 33c 2>/dev/null <br>
           cat /var/lib/dpkg/info/bandit7.password <br>
7 -> 8:    grep 'millionth' data.txt <br>
8 -> 9:    cat data.txt | sort | uniq -u <br>
9 -> 10:   strings data.txt | grep '=' <br>
10 -> 11:  cat data.txt | base64 -d <br>
11 -> 12:  cat data.txt <br>
           https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,13)&input=R3VyIGNuZmZqYmVxIHZmIFdJQU9PU0Z6TWpYWEJDMEtvU0tCYko4cHVRbTVsSUVp <br>
12 -> 13:  mkdir -p /tmp/xcn <br>
           cd /tmp/xcn && cat ~/data.txt | xxd -r > data <br>
           file data <br>
           mv data data.gz && gunzip data.gz <br>
           file data <br>
           mv data data.bz2 && bunzip2 data.bz2 <br>
           file data <br>
           mv data data.gz && gunzip data.gz <br>
           file data <br>
           mv data data.tar && tar xf data.tar <br>
           ls <br>
           file data5.bin <br>
           mv data5.bin data5.tar && tar xf data5.tar <br>
           ls <br>
           file data6.bin <br>
           mv data6.bin data6.bz2 && bunzip2 data6.bz2 <br>
           file data6 <br>
           mv data6 data6.tar && tar xf data6.tar <br>
           ls <br>
           file data8.bin <br>
           mv data8.bin data8.gz && gunzip data8.gz <br>
           ls <br>
           file data8 <br>
           cat data8 <br>
13 -> 14:  ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220 <br>
14 -> 15:  echo 'fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq' | nc -v 127.0.0.1 30000 <br>
15 -> 16:  openssl s_client -connect 127.0.0.1:30001 <br>
16 -> 17:  

</pre>

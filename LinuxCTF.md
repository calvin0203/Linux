#Linux指令練習
###ls
```
lab@29d4cf5af0ab:~$ ls
base64.txt  flag  hex.txt
```
```
cat flag
```

###ls -a
```
lab@29d4cf5af0ab:~$ ls -a
.  ..  .bash_logout  .bashrc  .hidden  .profile  base64.txt  flag  hex.txt
```
```
cat .hidden
```

###ls -l
```
lab@29d4cf5af0ab:~$ ls -l
total 12
-rw-rw-r-- 1 root root 46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root 35 Nov 15  2017 flag
-rw-rw-r-- 1 root root 68 Nov 20  2017 hex.txt
```
###ls -Al
```
total 28
-rw-r--r-- 1 lab  lab   220 Apr 26 14:48 .bash_logout
-rw-r--r-- 1 root root 3771 Apr 26 14:48 .bashrc
-rw-rw-r-- 1 root root   34 Nov 19  2017 .hidden
-rw-r--r-- 1 lab  lab   655 Apr 26 14:48 .profile
-rw-rw-r-- 1 root root   46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root   35 Nov 15  2017 flag
-rw-rw-r-- 1 root root   68 Nov 20  2017 hex.txt
```

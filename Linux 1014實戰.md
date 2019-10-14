# 實戰

### 題目：
```
cd
pwd
cat 
ls
top
ps
ping
```
### log
```
root@kali:~# pwd
/root
root@kali:~# cd ..
root@kali:/# pwd
/
root@kali:/# ls
0 	dev   initrd.img  	lib32   lost+found  opt   run   sys  var
bin   etc   initrd.img.old  lib64   media   	proc  sbin  tmp  vmlinuz
boot  home  lib         	libx32  mnt     	root  srv   usr  vmlinuz.old
root@kali:/#
```
### 答案
```
cd (change directory) // .. 回到上一層目錄 //
pwd (print name of current/working directory) 列出目前的工作目錄 //
ls 
```

### 創建資料夾、使用wget下載、使用gedit
```
root@kali:/# mkdir python
root@kali:/# cd python
root@kali:/python# wget https://www.flag.com.tw/bk/ex/f9751
--2019-10-14 03:49:17--  https://www.flag.com.tw/bk/ex/f9751
Resolving www.flag.com.tw (www.flag.com.tw)... 211.72.207.248
Connecting to www.flag.com.tw (www.flag.com.tw)|211.72.207.248|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘f9751’

f9751               	[ <=>            	] 	105  --.-KB/s	in 0s 	 

2019-10-14 03:49:17 (25.8 MB/s) - ‘f9751’ saved [105]

root@kali:/python# gedit test.py
root@kali:/python# ls
f9751  test.py
root@kali:/python#
```



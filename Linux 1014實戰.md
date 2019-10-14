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

### 創造、執行Python程式
```
root@kali:~# cd /
root@kali:/# cd python
root@kali:/python# gedit ch10-4test.py
root@kali:/python# python3 ch10-4test.py
Where do you live? Taiwan
Taiwan!
I hear it's nice there!
root@kali:/python# gedit ch10-5test.py
root@kali:/python# python3 ch10-5test.py
Enter a number to find the square of: 2
Enter a integer to find the square of: 5
25
root@kali:/python# gedit ch10-6test.py
root@kali:/python# python3 ch10-6.test.py
python3: can't open file 'ch10-6.test.py': [Errno 2] No such file or directory
root@kali:/python# python3 ch10-6test.py
Enter a number: 50
Enter another number: 23
50.0 * 23.0 = 1150.0
root@kali:/python# ^C
root@kali:/python#

```


### mkdir

```
指令名稱：mkdir
功能說明：建立目錄
語法：mkdir [options] directoryname
[options]
-m mode： --mode=模式 設定權限 <模式> (類似 chmod)，而不是 rwxrwxrwx 減 umask。
-p： --parents 需要時建立上層目錄，如目錄早已存在則不當作錯誤
-v： --verbose 每次建立新目錄都顯示訊息。

範例：
1.建立名稱為tech的目錄，但只允許擁有者有rwx的權限
#mkdir -m 700 tech

2.建立/home/tech/test目錄，但目前/home底下沒有任何目錄
#mkdir -p /home/tech/test

Source:https://blog.xuite.net/altohorn/linux/17259901-mkdir+%E5%BB%BA%E7%AB%8B%E6%96%B0%E7%9B%AE%E9%8C%84
```

### 實作
```
root@kali:~# cd Desktop/
root@kali:~/Desktop# mkdir KSU
root@kali:~/Desktop# ls
KSU
root@kali:~/Desktop#
```

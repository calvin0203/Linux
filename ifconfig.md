# Linux ifconfig 指令
### ifconfig
```

root@kali:~# ifconfig
docker0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
    	inet 172.17.0.1  netmask 255.255.0.0  broadcast 172.17.255.255
    	ether 02:42:0f:34:38:27  txqueuelen 0  (Ethernet)
    	RX packets 0  bytes 0 (0.0 B)
    	RX errors 0  dropped 0  overruns 0  frame 0
    	TX packets 0  bytes 0 (0.0 B)
    	TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
    	inet 10.0.2.15  netmask 255.255.255.0  broadcast 10.0.2.255
    	inet6 fe80::a00:27ff:fe02:feb2  prefixlen 64  scopeid 0x20<link>
    	ether 08:00:27:02:fe:b2  txqueuelen 1000  (Ethernet)
    	RX packets 12381  bytes 17632932 (16.8 MiB)
    	RX errors 0  dropped 0  overruns 0  frame 0
    	TX packets 4460  bytes 271997 (265.6 KiB)
    	TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
    	inet 127.0.0.1  netmask 255.0.0.0
    	inet6 ::1  prefixlen 128  scopeid 0x10<host>
    	loop  txqueuelen 1000  (Local Loopback)
    	RX packets 110  bytes 8676 (8.4 KiB)
    	RX errors 0  dropped 0  overruns 0  frame 0
    	TX packets 110  bytes 8676 (8.4 KiB)
    	TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
```
共有三種介面
docker0
eth0
lo
```
```

eth0 (乙太網)

列出IP位置(inet):10.0.2.15
網路子遮罩(netmask):255.255.255.0
最大傳輸單元(MTU):1500
廣播位置(Broadcast): 10.0.2.255


lo = localhost
IP位置:127.0.0.1
```
### Ping 10.0.2.15

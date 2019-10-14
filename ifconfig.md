# Linux ifconfig 指令
### ifconfig
```

lab@29d4cf5af0ab:~$ ifconfig
eth0      Link encap:Ethernet  HWaddr 02:42:ac:11:00:0d
          inet addr:172.17.0.13  Bcast:172.17.255.255  Mask:255.255.0.0
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
          RX packets:548544 errors:0 dropped:0 overruns:0 frame:0
          TX packets:977213 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:0
          RX bytes:51046489 (51.0 MB)  TX bytes:211407584 (211.4 MB)

lo        Link encap:Local Loopback
          inet addr:127.0.0.1  Mask:255.0.0.0
          UP LOOPBACK RUNNING  MTU:65536  Metric:1
          RX packets:2208 errors:0 dropped:0 overruns:0 frame:0
          TX packets:2208 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000
          RX bytes:122631 (122.6 KB)  TX bytes:122631 (122.6 KB)

```
```
eth0 (乙太網)

列出IP位置:172.17.0.13
網路遮罩:255.255.0.0
硬體MAC地址:02:42:ac:11:00:0d
```
### Ping 172.17.0.13

# ifconfig
```
docker0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        inet 172.17.0.1  netmask 255.255.0.0  broadcast 172.17.255.255
        ether 02:42:21:6d:47:cd  txqueuelen 0  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 10.0.2.15  netmask 255.255.255.0  broadcast 10.0.2.255
        inet6 fe80::a00:27ff:feb7:2183  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:b7:21:83  txqueuelen 1000  (Ethernet)
        RX packets 12430  bytes 17635530 (16.8 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 4726  bytes 287926 (281.1 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 20  bytes 1116 (1.0 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 20  bytes 1116 (1.0 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

```
```
有3個介面(interfaces):
[1]docker 0
[2]eth0 實體網卡
[3]lo==loaclhost每一台電曩都會有本地端位址  127.0.0.1
```
```
問題1.IP位址==172.17.0.1  
問題2.mtu 1500  最大傳輸單元Maximum Transmission Unit  https://en.wikipedia.org/wiki/Maximum_transmission_unit
問題1.MAC address==實體網卡位址==>ether 08:00:27:b7:21:83
問題1.
問題1.
問題1.lo==localhost address=?

```
## ip位置
```
inet==172.17.0.1 
```
## 網路遮罩
```
netmask==255.255.255.0
```

## 廣播
```
broadcast 10.0.2.255
```

## ipv6
```
inet6 fe80::a00:27ff:feb7:2183
```

## 實體網卡位置
```
ether 08:00:27:b7:21:83
```


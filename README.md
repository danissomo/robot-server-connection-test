# Тесты соединения робот-сервер
Модель usb модема: ```Huawei E8372```

Подключение: ```usb 2.0```

## Ping
### 1) wifi
```
64 bytes from 10.147.18.169: icmp_seq=1 ttl=64 time=6.81 ms
64 bytes from 10.147.18.169: icmp_seq=2 ttl=64 time=2.00 ms
64 bytes from 10.147.18.169: icmp_seq=3 ttl=64 time=2.27 ms
64 bytes from 10.147.18.169: icmp_seq=4 ttl=64 time=17.6 ms
64 bytes from 10.147.18.169: icmp_seq=5 ttl=64 time=26.6 ms
64 bytes from 10.147.18.169: icmp_seq=6 ttl=64 time=19.5 ms
64 bytes from 10.147.18.169: icmp_seq=7 ttl=64 time=37.2 ms
64 bytes from 10.147.18.169: icmp_seq=8 ttl=64 time=23.7 ms
64 bytes from 10.147.18.169: icmp_seq=9 ttl=64 time=6.83 ms
```
### 2) 4g
```
64 bytes from 10.147.18.169: icmp_seq=1 ttl=64 time=36.7 ms
64 bytes from 10.147.18.169: icmp_seq=2 ttl=64 time=23.7 ms
64 bytes from 10.147.18.169: icmp_seq=3 ttl=64 time=51.5 ms
64 bytes from 10.147.18.169: icmp_seq=4 ttl=64 time=41.0 ms
64 bytes from 10.147.18.169: icmp_seq=5 ttl=64 time=26.9 ms
64 bytes from 10.147.18.169: icmp_seq=6 ttl=64 time=37.1 ms
64 bytes from 10.147.18.169: icmp_seq=7 ttl=64 time=36.0 ms
64 bytes from 10.147.18.169: icmp_seq=8 ttl=64 time=35.8 ms
```
## Speed
### 1) wifi
```
------------------------------------------------------------
Client connecting to 10.147.18.169, TCP port 5001
TCP window size:  128 KByte (default)
------------------------------------------------------------
[  3] local 10.147.18.15 port 52678 connected with 10.147.18.169 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0-10.1 sec   136 MBytes   113 Mbits/sec
```
### 2) 4g
```
------------------------------------------------------------
Server listening on TCP port 5001
TCP window size:  128 KByte (default)
------------------------------------------------------------
[  4] local 10.147.18.169 port 5001 connected with 10.147.18.176 port 43626
[ ID] Interval       Transfer     Bandwidth
[  4]  0.0-11.4 sec  8.38 MBytes  6.15 Mbits/sec
```


## rostopic hz (images)
### 1) wifi
```
subscribed to [/realsense_back/color/image_raw]
average rate: 5.646
	min: 0.162s max: 0.192s std dev: 0.01235s window: 4
average rate: 5.890
	min: 0.144s max: 0.198s std dev: 0.01778s window: 10
average rate: 5.975
	min: 0.135s max: 0.198s std dev: 0.01764s window: 16
average rate: 5.790
	min: 0.135s max: 0.236s std dev: 0.02372s window: 21
average rate: 5.844
	min: 0.135s max: 0.236s std dev: 0.02470s window: 27
average rate: 5.850
	min: 0.135s max: 0.236s std dev: 0.02375s window: 33
```
```
subscribed to [/realsense_back/color/image_raw/compressed]
average rate: 30.348
	min: 0.007s max: 0.046s std dev: 0.00968s window: 29
average rate: 30.144
	min: 0.007s max: 0.057s std dev: 0.00938s window: 59
average rate: 30.089
	min: 0.007s max: 0.057s std dev: 0.00912s window: 89
average rate: 30.063
	min: 0.007s max: 0.057s std dev: 0.00907s window: 119
average rate: 30.025
	min: 0.007s max: 0.057s std dev: 0.00907s window: 149
^Caverage rate: 30.051
	min: 0.007s max: 0.057s std dev: 0.00880s window: 169
```

### 2) 4g
```
subscribed to [/realsense_back/color/image_raw]
no new messages
average rate: 1.822
	min: 0.516s max: 0.582s std dev: 0.03258s window: 3
average rate: 1.725
	min: 0.516s max: 0.641s std dev: 0.05110s window: 4
average rate: 1.598
	min: 0.516s max: 0.724s std dev: 0.07123s window: 6
average rate: 1.578
	min: 0.516s max: 0.724s std dev: 0.06741s window: 7
average rate: 1.559
	min: 0.516s max: 0.724s std dev: 0.06521s window: 8
average rate: 1.519
	min: 0.516s max: 0.794s std dev: 0.07481s window: 10
^Caverage rate: 1.565
	min: 0.516s max: 0.794s std dev: 0.07892s window: 12
```
```
subscribed to [/realsense_back/color/image_raw/compressed]
no new messages
average rate: 33.423
	min: 0.010s max: 0.045s std dev: 0.01158s window: 14
average rate: 31.075
	min: 0.007s max: 0.052s std dev: 0.01086s window: 45
average rate: 30.641
	min: 0.007s max: 0.052s std dev: 0.01064s window: 75
average rate: 30.533
	min: 0.007s max: 0.052s std dev: 0.00980s window: 105
average rate: 30.450
	min: 0.001s max: 0.068s std dev: 0.01004s window: 135
average rate: 30.376
	min: 0.001s max: 0.068s std dev: 0.00987s window: 166
average rate: 30.338
	min: 0.001s max: 0.072s std dev: 0.01111s window: 196
```
## Remote desktop
### 1) wifi

https://user-images.githubusercontent.com/37418257/193255204-438333fd-ac62-4af3-8c7d-2e2da6069e5c.mp4

### 2) 4g

https://user-images.githubusercontent.com/37418257/193849542-bda8bdd6-20cd-415b-aaea-7ead4c431552.mp4


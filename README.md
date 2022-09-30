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
```
### 2) 4g
```
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
## Remote desktop

### 1) wifi
[![wifi]()](wifi.mp4)
### 2) 4g
<video controls>
  <source src="4g.mp4" type="video/mp4">
</video>
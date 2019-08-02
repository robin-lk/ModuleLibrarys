### Robin的功能库
~~~txt
项目于9012/8/1创建，简单说就是一个多module的库，只要是能封装的，想到什么封装什么，没有那么多为什么。
~~~
##### BLE module - 蓝牙模块控制库

蓝牙技术联盟(SIG)后续发布的蓝牙4.1/4.2/5.0，都是同时包含低功耗蓝牙和经典蓝牙的。所以大家开发蓝牙应用的时候，一定要搞清楚自己是要开发低功耗蓝牙应用还是经典蓝牙应用，两者的应用场景是不同的。一般而言，经典蓝牙主要应用在蓝牙电话接听，蓝牙耳机，蓝牙音箱等场合，低功耗蓝牙应用在可穿戴设备，IoT智能设备，健身设备，蓝牙鼠标键盘等电池供电场合。当然，经典蓝牙也可以用电池供电，但LE对电池的要求更低，甚至可以用纽扣电池供电，而续航时间却很长，有的LE设备可以达到几年。
经典蓝牙和低功耗蓝牙两者物理层调制解调方式是不一样的，所以低功耗蓝牙设备和经典蓝牙设备两者之间是不能相互通信的，选型的时候千万不要搞混，如果主设备是低功耗蓝牙设备，从设备也必须是低功耗蓝牙设备；同样，经典蓝牙的从设备也只能和经典蓝牙的主设备进行通信。


![示意图](/img/Bluetooth-1.png)
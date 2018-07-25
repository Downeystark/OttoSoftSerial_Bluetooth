# Otto 软串口蓝牙控制
````
--- APP 原APP控制软件
--- libraries 库文件
--- OttoDIYAPP_122_baudrate9600_softSerial 软串口蓝牙控制.ino
````

### 使用方法

````
 1.原接线按OttoDIY+_InstructionsManual_V04.pdf接入
 2.更改蓝牙 tx,rx 分别 接引脚 D6,D7
````

### 为什么使用软串口

````
 原蓝牙接入方法占用tx,rx，导致usb端口不能直接刷入固件，使用软串口模拟 tx,rx ，
 即可 每次不需要拔下 蓝牙 刷入固件，更加方便
````


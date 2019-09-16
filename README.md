# TFminiPlus-Arduino

This application takes Uno board of Arduino as an example, writing related instructions of TFmini Plus, reading response data from LIDAR, processing and printing measurement data through Arduino, which helps customers to quickly familiarize themselves with our company's product and reduce development cycle.

TFmini Plus uses + 5V power supply and can connect 5V and GND of UNO board directly. It uses software serial port to communication, and defines software serial port name as Serial1 and define pin2 as RX and pin3 as TX. 

| No. | Color |Corresponding PIN|Funciton|Comment
|--|--|--|--|--
|1  | red |PIN-1|+5V|Power supply
|1  | white|PIN-2|RXD/SDA|TTL Receiving/Data
|1  | blue/green |PIN-3|TXD/SCL/IO|TTL Transmitting/I^2^C Clock/IO
|1  | black |PIN-4|GND|GND


![connect](https://img-blog.csdnimg.cn/20190910145208220.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zNzc1NDAzNg==,size_16,color_FFFFFF,t_70)
   


## Programming
The implementation of this example requires at least two serial ports of Arduino, one is for receiving radar data and the other is for displaying data to the computer. The following code can be copied and pasted into the IDE program editing window.

- [TFmini_PLUS_Setbaud_EN.ino](https://github.com/TFmini/TFminiPlus-Arduino/blob/master/Example-SetCommand/TFmini_PLUS_Setbaud_EN/TFmini_PLUS_Setbaud_EN.ino)

- [TFmini_PLUS_ReadData.ino](https://github.com/TFmini/TFminiPlus-Arduino/blob/master/Example-ReadData/ReadData/ReadData.ino)

## data review:

![review](https://img-blog.csdnimg.cn/20190910145218835.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zNzc1NDAzNg==,size_16,color_FFFFFF,t_70)

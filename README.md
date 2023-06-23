# [Xindex](https://doc.soc.xin/)

## [Wi-Fi](https://doc.soc.xin/application/wifi)


## [Bluetooth](https://doc.soc.xin/application/bluetooth)

其中4.0版本之前的版本是经典蓝牙，从4.0版本开始，低功耗蓝牙诞生了，简称BLE，它与之前的蓝牙设备最显著的区别是，功耗更低。

BLE 使用2.4GHz工业、科学及医疗(ISM)频段，从2400MHz~2483.5MHz约 83.5MHz的频谱资源。采用的 GFSK 调制方式(髙斯频移键控)，物理层的比特率为 1Mbit/s(1Mbps)。

一共 40 个通道，37 个自适应自动调频数据通道用于两个连接 设备的通讯，3 个固定广播通道分别是 37、 38、 39。

### [Bluetooth v5.4](https://www.bluetooth.com/wp-content/uploads/2023/02/2301_5.4_Tech_Overview_FINAL.pdf)

* 支持带响应的周期性广播（PAwR）
PAwR是一个新的BLE逻辑传输层，是一种支持无连接的、双向的、一对多的、一种低功耗拓扑技术。
* 支持加密的广播数据（EAD）
该特性提供了一种标准化的方法来加密广播包中的数据，加密后的广播数据只能被拥有相同密钥的设备解密。 当然广播包的加密是需要两个设备建立gatt连接之后，才会生成加密广播包的密钥。
* LE GATT 安全级别特征
设备现在可以使用GATT 安全级别特性来表示设备的安全模式和安全等级
* 广播编码选择
当发送BLE扩展广播的时候，现在可以选择使用哪种Codec编码方式来发送。

#### PAwR

蓝牙5.4规范的主要改进之一就是实现了单个接入点与数千个终端节点进行双向无连接通信， 这一特性主要是针对电子货架标签（Electronic Shelf Label，ESL）市场。

### [Bluetooth v5.3](https://www.bluetooth.com/wp-content/uploads/2021/01/Bluetooth_5.3_Feature_Enhancements_Update.pdf)

蓝牙5.3的传输速度要比5.0高了1倍以上。同时，数据传递量也达到了蓝牙5.0的800%左右。可见，蓝牙5.3能够拥有更快的传输速度和数据收发量。

由于增强了传输速度，蓝牙5.3的传递距离也提高到了5.0的4倍。从理论距离来看，它的工作距离能达到300米，不过条件比较苛刻。在日常使用的时候，蓝牙5.3的传输距离在穿墙能力和距离上也更优秀。

除了距离和速度外，还有一些额外的功能不同。例如蓝牙5.3新增了低速率模式、周期性广播增强功能。同时它所能传递的数据包也不同，从而降低了传递过程中的信号损耗。


* [CH583](https://doc.soc.xin/CH583)

### [Bluetooth v5.2](https://www.bluetooth.com/wp-content/uploads/2020/01/Bluetooth_5.2_Feature_Overview.pdf)

2020年1月6日发布，相较 Bluetooth 5.1 版本新增的功能主要包括LE同步信道(LE Isochronous Channels), 增强版ATT(Enhanced ATT)及LE功率控制(LE Power Control)。

### [Bluetooth v5.1](https://www.bluetooth.com/wp-content/uploads/Files/Specification/1901_Feature_Overview_Brief_FINAL.pdf)

2019年1月28日发布，相较 Bluetooth 5.0 加入了测向功能和厘米级的定位服务，即Angle of Arrival (AoA) and Angle of Departure (AoD)（到达角/出发角），这项功能的加入使得室内的定位会变得更加精准，并且在小物体的位置上也能准确定位避免物品遗失。

### [Bluetooth v5.0](https://www.bluetooth.com/wp-content/uploads/2019/03/Bluetooth_5-FINAL.pdf)

2016年12月发布，支持2M PHY，速度最高为。比之前版本的1M PHY拥有两倍的传输速度。同时支持LE long range，通过125K或500K PHY实现更远的广播距离和传输距离，

蓝牙mesh的推出，网状网络可以将成千上万个设备互联。

更快的传输速度将在提升频谱和能量效率的同时，使数据传输速率加倍，大幅降低功耗，并且可以实现诸如音频等全新的更高吞吐量应用，单包数据由原来蓝牙4.0的20字节扩展到蓝牙4.2的256字节。

传输距离提高了4倍,蓝牙5标准的覆盖范围将是蓝牙4.2 的4 倍。

广播模式信息容量提高了8倍。其广播通信容量从蓝牙4.2的31Byte升级成为255Byte，增强的广播能力将带来更好的信标，以创建更多基于位置的室内定位服务和导航服务，室内定位的精度小于1米, 提升室内定位精确度功能。

### [Bluetooth v4.2](https://www.bluetooth.com/zh-cn/specifications/specs/core-specification-4-2/)


2014年12月发布，改善了数据传输速度和隐私保护程度。将发送数据包长度扩展，提升数据传输速度；新增LE安全配对，增加隐私保护程度

* 蓝牙4.2最大通讯速度为1Mbps
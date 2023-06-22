# [Xindex](https://doc.soc.xin/)

## Bluetooth

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

* [CH583](https://doc.soc.xin/CH583)
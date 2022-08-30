# 模拟蓝牙设备
在蓝牙扫描结果中模拟一个 BLE 外围设备通告。  
支持动态通告数据同步，需要另一台 Android 5.0 以上的设备作为监听设备，安装`蓝牙通告监听器`，并创建一个[LeanCloud](https://www.leancloud.cn/) 应用用于云端同步。  
仅用于蓝牙设备的开发与调试，请勿用于签到打卡等违法违纪用途。
## 使用说明
关闭模块状态下，使用 nRF Connect 扫描得到要模拟的通告信号，将结果填入对应选项。
* `Raw data` 去掉开头的 `0x` 填入`通告数据`
* 支持 Android 8.0 或更高版本

<p align="center">
  <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/com.ztc1997.mockbluetoothdevice/master/img/howto.jpg"/>
</p>

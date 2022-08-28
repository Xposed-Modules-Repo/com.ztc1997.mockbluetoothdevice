# 模拟蓝牙设备
在蓝牙扫描结果中模拟一个 BLE 外围设备广播。仅用于蓝牙设备的开发与调试，请勿用于签到打卡等违法违纪用途。
## 使用说明
关闭模块状态下，使用 nRF Connect 扫描得到要模拟的广播信号，将结果填入对应选项。
* `Raw data` 去掉开头的 `0x` 填入`广播数据`
* 支持 Android 8.0 或更高版本
<p align="center">
  <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/com.ztc1997.mockbluetoothdevice/master/img/howto.jpg"/>
</p>
<div align="center">
  <p>
    <img src="https://img.shields.io/badge/Hackintosh%20ThinkPad-L490-red.svg" alt="ThinkPad-L490">
  </p>
</div>

>小白一枚，记录黑苹果折腾历程

### 机器配置信息
型号 | ThinkPad L490
---|---
CPU | Intel Core i5-8265U
核显 | UHD Graphics 620	
有线网卡 | Intel Ethernet Connection I219-V
无线网卡 | Intel Wireless-AC 9260

### 更新

- 2019-11-21 显卡驱动正常；声卡驱动正常，声音调节正常；触摸板设置正常

- 2019-11-22 蓝牙驱动正常

- EFI v1.0 已知问题：开机存在闪屏；电源驱动不正常

- EFI v2.0 2020-06-12 从 :heart: 出发，新增EFI for Install

- 2020-07-09 更新clover到5103，重新定制 EFI v2.1， 发布rc1版（beat1忘了具体更新的内容），驱动正常部分包括（电源、显卡、声音、网卡、
蓝牙）

### 驱动正常

- 原生电源
- 睡眠
- 显卡
- HDMI外接显示器正常，Type-c外接显示器驱动正常
- 声卡，Fn快捷键
- 小太阳，Fn快捷键
- 有线网卡
- 无线网卡
- USB、Type-c
- 蓝牙

### 已知问题

- 睿频
- 快捷键个别情况 存在破音
- ~~无线网卡使用[itlwm](https://github.com/OpenIntelWireless/itlwm) 驱动，目前测试正常，但不稳定    建议购买拆机卡或USB网卡~~
- 触摸板强制开启，只能使用轻点，无法使用多指手势，设备_CID：`PNP0F13`，若有知道解决的大佬，欢迎Issue

### 测试

- 使用 <b>EFI v1.0</b> 安装10.15.5(19B88)测试通过
- 使用 <b>EFI v2.0</b> 安装10.15.4(19E2269)测试通过
- 使用 <b>EFI v2.1-rc1</b> 安装10.15.5(19F101)测试通过

### 致谢

- [@黑果小兵](https://github.com/daliansky)
- [@acidanthera](https://github.com/acidanthera)
- [@OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm)


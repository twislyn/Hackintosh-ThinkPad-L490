<div align="center">
  <p>
    <img src="https://img.shields.io/badge/Hackintosh%20ThinkPad-L490-red.svg" alt="ThinkPad-L490">
  </p>
</div>

>小白一枚，记录黑苹果折腾历程

### 机器配置信息
型号 | ThinkPad L490
---|---
CPU系列 | 第八代智能英特尔酷睿i5
CPU型号 | i5-8265U
CPU主频 | 1.6Ghz
最高睿频 | 3.9Ghz
核心架构 | Whiskey Lake
硬盘容量 | 500GB(SATA HDD) + 128GB(M.2 SSD)
光驱类型 | 无光驱
屏幕尺寸 | 14.0英寸
显示比例 | 16:9
屏幕分辨率 | 1366x768
屏幕技术 | LED背光;TN防眩目显示屏
显卡类型 | 集成显卡
显卡芯片 | Intel UHD Graphics 620
音频系统 | HD Audio, Realtek ALC3287 codec
无线网卡 | Intel 9260(2x2 AC)
有线网卡 | Intel  I219-V
蓝牙 | BT 5.0
数据接口 | 2个USB3.1,2个Type-C
视频接口 | HDMI
读卡器 | Micro SD读卡器
指取设备 | TrackPad 经典触控板 多点触控


### 更新

- 2019-11-21 显卡驱动正常；声卡驱动正常，声音调节正常；触摸板设置正常

- 2019-11-22 蓝牙驱动正常

- EFI v1.0 已知问题：开机存在闪屏；电源驱动不正常

- EFI v2.0 2020-06-12 从 :heart: 出发，新增EFI for Install

- 2020-07-09 更新clover到5103，重新定制 EFI v2.1， 发布rc1版（beat1忘了具体更新的内容:joy:），驱动正常部分包括（电源、显卡、声音、网卡、
蓝牙）

- 2020-07-30 增加OC EFI

### 驱动正常 :+1:

- 原生电源
- 睡眠
- 显卡
- HDMI及Type-c外设
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
- 触摸板强制开启，只能使用轻点，无法使用多指手势，设备_CID：:point_right: PNP0F13 :point_left:，若有知道解决的大佬，欢迎issue

### 测试

- 使用 <b>EFI v1.0</b> 安装10.15.5(19B88)测试通过
- 使用 <b>EFI v2.0</b> 安装10.15.4(19E2269)测试通过
- 使用 <b>EFI v2.1-rc1</b> 安装10.15.5(19F101)测试通过

### 致谢

- [@黑果小兵](https://github.com/daliansky)
- [@acidanthera](https://github.com/acidanthera)
- [@OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm)


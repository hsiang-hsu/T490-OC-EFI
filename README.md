# T490-OC-EFI-Monterey 12.3.1
## 引导简介

……

## 硬件参数

- CPU：i7-10510U
- 显卡：UHD630
- 声卡：RealtekALC257
- 硬盘：Kinston SA2000M81000G
- 内存：Samsung DDR4
- WIFI：I219-V
- 蓝牙：AX201

## 正常工作

1. 显卡
2. 声卡
4. 蓝牙
5. WiFi
6. 以太网
7. ……

## 不正常工作

1. SD卡无法驱动；
3. 隔空投送无法工作；
3. ……；

## 需要修改

1. PlatformInfo->Generic->MLB：需要修改；
2. PlatformInfo->Generic->SystemProductName：需要修改；
3. PlatformInfo->Generic->SystemSerialNumber：需要修改；
4. PlatformInfo->Generic->SystemUUID：需要修改。
5. ……

## OC版本及更新日志

| 日期           | OC版本 | 系统版本        | 更新日志                                                     |
| -------------- | ------ | --------------- | ------------------------------------------------------------ |
| 2022年05月01日 | 0.7.6  | Monterey 12.3.1 | 修复Monterey下蓝牙无法连接问题                               |
| 2022年04月25日 | 0.7.6  | Monterey 12.3.1 | 更新驱动：AppleALC，RealtekCardReader，RealtekCardReaderFriend |
| 2022年04月12日 | 0.7.6  | Monterey 12.3.1 | 正常引导                                                     |

## 特别感谢

1. A huge thanks to [dortania](https://dortania.github.io/OpenCore-Install-Guide/) for their incredibly detailed guide.
1. https://github.com/yusifsalam/t490-macos

# B85ProGamer-i5-4460-Hackintosh-OC
ASUS B85 Pro Gamer i5-4460 Hackintosh Opencore0.6.1 working at Catalina 10.15.6.

Theoretically works on Big Sur.

## device list
| Name            | Device                    | Info                                                         |
|-----------------|---------------------------|--------------------------------------------------------------|
| CPU             | i5-4460                                                      | normal frequency shift                                       |
| iGPU            | HD4600                                                       | 4K decode normal，framebuffer injected，HEVC decode can‘t use |
| Audio           | ACL1150                                                      | layout-id：5，injected，3.5 on the case normal, others no test |
| NetWork         | I1217v                                                       | normal                                                       |
| Wifi&Bluetooth  | FV-T919                                                      | BCM94360CD                                                   |
| USB             | 4\*USB2.0 and 2\*USB3.0 on board，<br />2\*USB2.0 and 2\*USB3.0 on case | customlized by kext                                          |
| Serial/UUDI/MLB | generated                                                    | But highly recommend you to gen yours                        |

## issues
1、HD4600 still have gray screen porblems, restart the monitor can reduce it. Only Martians know how to fix it. :(

there is a way to reduce the gray screen posibility.

在偏好设置-显示器-颜色中固定描述文件为macOS自带的可减缓灰屏，这样做之后灰屏仅在重启时出现

## Changelog
### v1.0(2020-09-10)
frist upload
### v1.1(2020-09-10)
add SSDT-GPRW.aml to fix the hibenation problem.
### v1.2(2020-10-01)
fix the iPad connection problems.

update SMBIOS to iMac15,1 to support the macOS 11 Big Sur.

## Credits
@intel for CPUs.

@apple for macOS.

@acidanthera thanks for creating opencore.

@ske1996 for leading me to Hackintosh.

## Pictures
![img1](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic1.jpg)

![img2](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic2.jpg)


# B85ProGamer-i5-4460-Hackintosh-OC
ASUS B85 Pro Gamer i5-4460 Hackintosh Opencore0.6.1 working at Catalina 10.15.6.

Theoretically works on Big Sur.

## device list
| Name            | Device                    | Info                                                         |
|-----------------|---------------------------|--------------------------------------------------------------|
| CPU             | i5-4460                   | normal frequency shift                                       |
| iGPU            | HD4600                    | 4K decode normal，framebuffer injected，HEVC decode can‘t use |
| dGPU            | GTX960                    | blocked                                                      |
| Audio           | ACL1150                   | layout-id：5，injected，3.5 on the case normal, others no test |
| NetWork         | I1217v                    | normal，I have no WiFi and Bluetooth installed               |
| USB             | 4\*USB2.0，2\*USB3.0 on board | customlized by kext                                          |
| Serial/UUDI/MLB | generated                 | Highly recommend you to gen yours                            |

## issues
1、still some problems with usb，it can't detect my ipad. But Android Phones and USB devices works normally. 

2、HD4600 still have gray screen porblems, restart the monitor can fix it. Only Martians know how to fix it. :(

## Pictures
![img1](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic1.jpg)

![img2](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic2.jpg)

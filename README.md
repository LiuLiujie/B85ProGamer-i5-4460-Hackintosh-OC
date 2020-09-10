# B85ProGamer-i5-4460-Hackintosh-OC
ASUS B85 Pro Gamer i5-4460 Hackintosh Opencore0.6.1 working at Catalina 10.15.6
Theoretically works on Big Sur

device list
| Name            | Device                    | Info                                                         |
|-----------------|---------------------------|--------------------------------------------------------------|
| CPU             | i5-4460                   | normal frequency shift                                       |
| iGPU            | HD4600                    | 4K decode normal，framebuffer injected，HEVC decode can‘t use |
| dGPU            | GTX960                    | blocked                                                      |
| Audio           | ACL1150                   | layout-id：5，injected，3.5 on the case normal, others no test |
| NetWork         | I1217v                    | normal，I have no WiFi and Bluetooth installed               |
| USB             | 4\*USB2.0，2\*USB3.0 on board | customlized by kext                                          |
| Serial/UUDI/MLB | generated                 | Highly recommend you to gen yours                            |

# B85ProGamer-i5-4460-Hackintosh-OC
ASUS B85 Pro Gamer i5-4460 Hackintosh Opencore0.6.7 working at Big Sur 11.2.2.

## Device list
| Device          | Type                                                         | Infomation                                                   |
| --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| CPU             | i5-4460                                                      | normal frequency shift                                       |
| iGPU            | HD4600                                                       | 4K decode normal，framebuffer injected，HEVC decode can‘t use |
| dGPU            | RX560D                                                       | Normal                                                       |
| Audio           | ACL1150                                                      | layout-id：5，injected，3.5 on the case normal, others no test |
| NetWork         | I1217v                                                       | normal                                                       |
| Wifi&Bluetooth  | FV-T919                                                      | BCM94360CD                                                   |
| USB             | 4\*USB2.0 and 2\*USB3.0 on board，<br />2\*USB2.0 and 2\*USB3.0 on case | customlized by kext                                          |
| Serial/UUDI/MLB | generated                                                    | But highly recommend you to gen yours                        |

## BIOS Settings
<img src="https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/bios1.png" width = "291.5" height = "407.5" alt="" align=center />

<img src="https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/bios2.png" width = "118" height = "66.5" alt="" align=center />

## Issues
(Not found for mine)

## common Issus
1、Gray screen when restart the macOS

Try to fix the Display colors and calibration in preference. Restart the monitor can fix it.

2、Hibernation or Sleep problem

Follow the BIOS Settings above can always fix it.If can't, please check the log and fix yourself.

Somebody with dGPU said he can't wake the system from sleep by mouse or keyboard. But can wake it by Power Button on case.

Update:Now I have dGPU but hibernation or sleep are normal.

## Changelog
### v1.0(2020-09-10)
frist upload
### v1.1(2020-09-10)
add SSDT-GPRW.aml to fix the hibenation problem.
### v1.2(2020-10-01)
fix the iPad connection problems.

update SMBIOS to iMac15,1 to support the macOS 11 Big Sur.
### v1.2_special(2020-10-04)(no release)
add NVMe module into bios and use HP NVME EX920 as system disk.

If you do the same, please search 'NVMeFix' in github and add this kext into your EFI.
### v1.3(2020-10-06)
update to oc0.6.2 and some kexts.
### v1.3.1(2020-10-09)(no release)
allow reset nvram button in OC menu.

only change in repo, no release, you can search AllowNvramReset in config.plist and open it.
### v1.4(2020-10-16)
fix sleep problem, thanks @Wyeme
### v1.5(2020-11-07)
update to oc0.6.3 and some kexts
### v1.6(2020-12-20)
update to oc0.6.4 to OTA big sur
### v1.7(2020-03-02)
update to oc0.6.7
## Credits
@intel for CPUs.

@apple for macOS.

@AMD for dGPU

@acidanthera thanks for creating opencore.

@ske1996 for leading me to Hackintosh.

## Pictures
![img1](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic1.jpg)

![img2](https://github.com/LiuLiujie/B85ProGamer-i5-4460-Hackintosh-OC/blob/master/pics/pic2.jpg)


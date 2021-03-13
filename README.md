# Alienware-Opencore-Theme
Alienware Opencore Theme 👽
![rockjesus-octheme](https://user-images.githubusercontent.com/23656651/110778693-a2ef4c00-829d-11eb-8819-6869312ffd76.png)
操作指南： 仅适用于OC0.6.5 正式版及以上版本

下载此附件中Resources文件夹替换EFI/OC/同名文件夹；

EFI/OC/Drivers/中必须存在CrScreenshotDxe.efi（截图快捷键驱动） 并在config.plist加载该驱动；

替换oc文件夹下的resource文件夹，config-misc-boot-pickervariant-modern

Setup：
Replace EFI > OC > Resources
config.plist：
Misc > Boot > PickerVariant: Modern
Custom Icon Setup (Linux icon etc.)
Misc > Boot > PickerAttribute: 17

# Alienware 17 R4 长期维护 Long-term maintenance：https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-Mojave-10.14-Hackintosh

# 更多台式机型 More desktop models: https://github.com/jianghaizhi/DELL-Alienware-Aurora-R7-macOS

# Guides [中文版](https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra/blob/master/README.md)|||[English](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-Mojave-10.14-Hackintosh/blob/master/README.md)|||[subwoofer](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/alc.md)|||[hdmi audio](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/hdmi.md)|||[led light](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/light.md)|||[mouse theme](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/mouse.md)|||[clover theme](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/theme.md)|||[thunderbolt](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/tb.md)|||[Q&A](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/guide/qa.md)|||[远景论坛](http://bbs.pcbeta.com/viewthread-1833933-1-1.html)|||[tonymacx86](https://www.tonymacx86.com/threads/guide-alienware-17-r4-dual-gpu-macos-mojave-10-14-hackintosh.288728/)

# 欢迎来我的博客 Welcome to my blog：https://rockjesus.cn


# 黑果小兵的部落阁 daliansky's blog: https://blog.daliansky.net （安装教程等新手看这里）

# 其他各品牌机型 other brands:
https://github.com/daliansky/Hackintosh
https://zhih.me/hackintosh/#/


# 黑苹果常用网站 credits:
http://bbs.pcbeta.com/
https://www.insanelymac.com/
https://www.tonymacx86.com/
https://github.com/acidanthera/Lilu
https://bitbucket.org/RehabMan/


# 外星人电脑黑苹果驱动情况总结:
1.首先win下-设备管理器-监视器-通用即插即用监视器
-常规-位置-确认显示器链接的显卡是双显还是只有独显,
 A:可切换显卡机型(双显FN+F7切换模式)10.13.6下安装webdriver可驱动双显卡,可以3种模式运行(单核显模式需ssdt等屏蔽独显节能省电,单独显模式需win下切换支持外接显示器,双显卡模式支持外接显示器),10.14/15下只能用核显
 B:不可切换显卡机型(只有N卡输出GSYNC版本默认屏蔽核显)配合webdriver只能安装最高到10.13.6,如果安装10.14/15显卡无解
 C:黑苹果只支持10x0系列以下n卡,16x0/20x0系列显卡无解
 
 
2.killer 有线网卡和蓝牙可驱动, 无线网卡无解,推荐换内置无线网卡DW1560,
dw1820问题多多麻烦，dw1830有点大装不进去，
intel有线网卡蓝牙可驱动，无线网卡暂时无解


3.大家有补充的可以@我

# 如有疑问请进QQ群 If u need help >> https://gitter.im/Alienware-hackintosh/community

| 微信圈子                                                                                                                                                              | 微信小程序                                                                                                                                                              | 微信公众号                                                                                                                                                                                                                                                                                                                            | 
| ----------------------------------------------------------   | ----------------------------------------------------------   | ----------------------------------------------------------   |  
| ![image](https://user-images.githubusercontent.com/23656651/111026490-78c89600-8425-11eb-97b1-c037751acf41.jpg)
 | ![image](https://user-images.githubusercontent.com/23656651/111026497-8251fe00-8425-11eb-9fee-d9c646e49f66.png)
 | ![image](https://user-images.githubusercontent.com/23656651/111026513-9269dd80-8425-11eb-835e-2ff3c0f646b4.jpg)
 | 
# ************ BUY ME A COFFEE & JOIN US ************
| 外星人黑苹果QQ群：308469644                                                                                                                                                              | 支付宝打赏                                                                                                                                                              | 微信打赏                                                                                                                                                              |  微信赞赏                                                                                                                                                              | 
| ----------------------------------------------------------   | ----------------------------------------------------------   | ----------------------------------------------------------   |  ----------------------------------------------------------   | 
| ![image](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-Mojave-10.14-Hackintosh/blob/master/qq.png?raw=true)![qq](https://user-images.githubusercontent.com/23656651/111026572-cc3ae400-8425-11eb-970a-917928bb55d8.png)
 | ![image](https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra/blob/master/zfb.jpeg) | ![image](https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra/blob/master/wx.jpeg) | ![image](https://github.com/RockJesus/Alienware-17-R4-Dual-GPU-MacOS-10.15-14-13-Hackintosh/blob/master/zsm.png?raw=true) |

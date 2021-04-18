# ASUS-ZenBook-UX510UX-U5000UX-Hackintosh OpenCore / Clover

i5-7200U
12G内存(4+8)
NVDIA GTX950M 2G
浦科特M9 NVMe 512G (原镁光256G M.2)

### 使用 OpenCore 过程

参考 https://github.com/nlg96/Opencore-Asus-Ux510ux 的config.plist使用OCC配置器修改

更新OC 0.6.5 MOD版 及 OC 0.6.8 MOD 运行正常并增加图形启动界面 （感谢远景大神 btwise 发布的MOD版）



### 使用Clover 过程(停用而且不再折腾)

最早使用Clover 的config.plist取自

https://www.tonymacx86.com/threads/asus-zenbook-ux510ux-remaining-minor-issues.281152/page-2 

修改配置文件几处及加了Intel蓝牙和网卡驱动 https://github.com/OpenIntelWireless/itlwm 运行正常

开启核显并补丁，屏蔽独显，GTX950M无解，

隔空投送能看到无法传送文件，也算无解，等大神能否有新突破

蓝牙正常，wifi可接5G 网速略win低一些,睡眠正常，音频切换正常

HDMI外接切换，音频输出都正常

Type-C 端口正常，接移动硬盘速度正常，转DP及HDMI可以使用

USB正常，3.0速度正常

键盘灯快捷键，屏幕亮度快捷键，声音快捷键正常使用并能出现界面提示图标

每次Clover版本更新需修改的参数也不多，轻松升级

对比后来使用的OC主观感觉效能和稳定OC略胜些


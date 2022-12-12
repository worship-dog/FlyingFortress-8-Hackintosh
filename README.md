# FlyingFortress-8-Hackintosh
飞行堡垒8黑苹果EFI
---
继dell-7559之后的又一自制efi

opencore version 0.8.7

os version Ventura 13.0.1

触摸板为i2c类型，需要使用VooDooI2CHID.kext才能驱动，而目前由于VooDooI2CHID.kext存在的问题，在Ventura系统下会出现USB控制器异常，具体表现为关机自动重启或者蓝牙不可用(刚开机时可用)，如无需使用触摸板，可自行修改EFI取消勾选VooDooI2CHID.kext以正常使用蓝牙功能。

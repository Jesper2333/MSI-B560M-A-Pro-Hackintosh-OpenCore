# MSI-B560M-A-Pro-Hackintosh-OpenCore

MSI B560M-A-Pro 黑苹果 (OpenCore引导，Monterey 12.1测试通过) 

提供四份针对不同CPU的配置

 配置说明|（MSI-B560M-A-Pro-iGPU.zip） |
 ----|-----|
 CPU|支持10代i7、i5、i3（i7-10700、i3-10105经测试通过）
 核显|Intel UHD Graphics 630（显示输出黑屏，必须搭配免驱独立显卡）
 
 配置说明|（MSI-B560M-A-Pro-Base.zip） |
 ----|-----|
 CPU|支持10代无核显i7、i5、i3
 核显|无
 
 配置说明|（MSI-B560M-A-Pro-i9-iGPU.zip） |
 ----|-----|
 CPU|支持10代i9
 核显|Intel UHD Graphics（显示输出黑屏，必须搭配免驱独立显卡）
 
 
 配置说明|（MSI-B560M-A-Pro-i9-Base.zip） |
 ----|-----|
 CPU|支持10代无核显i9
 核显|无

**BIOS设置**
BIOS设置提醒
-

1、关闭Secure Boot

2、关闭Fast Boot

3、关闭TPM2.0

4、启动改为纯UEFI（关闭CSM）

5、如果CPU带有核显，请开启核显，DVMT设置为64MB

6、必须关闭MSR


已知存在的问题（系统：macOS Monterey 12.1）
-

1、核显可以驱动，硬件加速正常，但输出接口无法使用，必须搭配免驱独立显卡。


运行效果图
-
![1](https://github.com/Jesper2333/MSI-B560M-A-Pro-Hackintosh-OpenCore/blob/main/p1.jpg)

![2](https://github.com/Jesper2333/MSI-B560M-A-Pro-Hackintosh-OpenCore/blob/main/p2.jpg)

![3](https://github.com/Jesper2333/MSI-B560M-A-Pro-Hackintosh-OpenCore/blob/main/p3.jpg)

![4](https://github.com/Jesper2333/MSI-B560M-A-Pro-Hackintosh-OpenCore/blob/main/p4.jpg)

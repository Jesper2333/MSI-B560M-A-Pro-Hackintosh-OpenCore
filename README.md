# MSI-B560M-A-Pro-Hackintosh-OpenCore

MSI B560M-A-Pro 黑苹果 (OpenCore引导，Monterey 12.1测试通过) 

 配置| |
 ----|-----|
 CPU|Intel Core i7-10700
 核显|Intel UHD Graphics 630（显示输出黑屏，必须搭配免驱独立显卡）

**BIOS设置**
BIOS设置提醒
-

1、关闭Secure Boot

2、关闭Fast Boot

3、关闭TPM2.0

4、启动改为纯UEFI（关闭CSM）

5、开启核显，DVMT设置为64MB

6、必须关闭MSR


已知存在的问题（系统：macOS Monterey 12.1）
-

1、核显可以驱动，硬件加速正常，但输出接口无法使用，必须搭配免驱独立显卡。


运行效果图
-
![1](https://github.com/Jesper2333/Acer-A715-Hackintosh/blob/main/p1.png)

![2](https://github.com/Jesper2333/Acer-A715-Hackintosh/blob/main/p2.png)

![3](https://github.com/Jesper2333/Acer-A715-Hackintosh/blob/main/p3.png)



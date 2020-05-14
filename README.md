# ASUS-Z370-F-i7-8700K-macOS
Hackintosh  10.14 mojave &amp; 10.15 catalina 华硕Z370-F黑苹果EFI配置和教程

## 硬件配置

- ✅ 主板：ASUS ROG STRIX Z370-F GAMING
- ✅ CPU：Intel 8700K
- ✅ 显卡：蓝宝石RX590 8G D5 超白金极光特别版
- ✅ 内存：金士顿骇客神条 Predator DDR4 2933 8G * 2
- ✅ 以太网卡：Intel I219V2 PCI Express Gigabit Ethernet（主板自带）
- ✅ 无线网卡&蓝牙：BCM943602CS（另购）
- ✅ 存储：SanDisk Ultra 3D NVMe
- ✅ 显示器：DELL U2718Q

详细安装说明：https://mp.weixin.qq.com/s/KOZiXMBKx13EYeQrAn7E5g

公众号：黑星软件店

## 主要步骤

1. 找一台运行macOS的电脑，在App Store里面搜索下载目标版本的macOS系统
2. 准备一个U盘，格式化U盘，并使用对应版本的UniBeast将系统写入到U盘
3. 使用本项目的对应的EFI替换U盘中的EFI
4. 设置BIOS
   - 关闭**VT-d**
   - 关闭**CFG-Lock**
   - 关闭**Secure Boot Mode**
   - 选择系统类型为 **Other OS**
   - 关闭**IO Serial Port**

5. 使用U盘启动电脑
6. 使用磁盘工具格式化目标硬盘
7. 将macOS安装到目标硬盘（会有多次重启）
8. 成功安装macOS后，U盘中的EFI文件复制到硬盘中的EFI
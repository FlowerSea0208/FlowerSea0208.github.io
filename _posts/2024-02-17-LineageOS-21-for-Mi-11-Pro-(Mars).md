---
title: LineageOS 21 for Mi 11 Pro (Mars)
updated: 2023-02-17 06:10
---

# 适用于小米 11 Pro（mars）的 LineageOS 21.0

## 下载：[GitHub](https://github.com/FlowerSea0208/flower-ota/releases/tag/mars-21-240217)
* 警告：下载链接中所包含的构建版本包括我所拥有的其他设备的构建版本，请确保从该特定设备的版本中下载所需文件，例如：“LineageOS 21.0 forxiaomi Mi 12S (mayfly)”

## 安装:

请确保你下载了以下文件
* boot.img
* dtbo.img
* vendor_boot.img
* recovery.img
* lineage-21.0-20240217-UNOFFICIAL-mars.zip

请使用fastboot/adb安装它们

* fastboot flash boot boot.img
* fastboot flash dtbo dtbo.img
* fastboot flash vendor_boot vendor_boot.img
* fastboot flash recovery recovery.img

命令格式为：fastboot flash 分区 相应分区文件地址

完成后请重启到recovery模式

* fastboot reboot recovery

然后使用adb刷入ROM
* adb sideload lineage-21.0-20240217-UNOFFICIAL-mars.zip

等待recovery模式中出现yes/no的选项，如果你需要gapps请在选择yes重启recovery后使用adb刷入gapps，否则no

## 其余内容
内核源代码及设备树开源地址[在这里](https://github.com/xiaomi-mars-devs)

构建时间：2024年3月2日

构建类型：unofficial（非官方）
Selinux：enforce

没有内置gapps，如需请查阅[lineageOS wiki](https://wiki.lineageos.org/gapps/)

内置固件

## 捐赠以支持开发

* 向我捐赠 [PayPal](https://paypal.me/FlowerSea0208) [微信](https://s2.loli.net/2022/10/15/wHpjyhP2b4LR3IG.png) [支付宝](https://s2.loli.net/2022/10/15/DSlCcnpJbQHR8Tw.jpg)

* 通过PayPal向@ArianK16a捐赠Donate via PayPal to ArianK16a

* 通过PayPal向lineageOS组织捐赠https://www.paypal.me/LineageOS

---
title: Evolution X 7.x for Mi 11 Pro (Mars/Star)
updated: 2022-11-02 12:43
---

![Evolution X](https://i.imgur.com/IvlZLyc.png)

## Keep Evolving
**Pixel UI, customization, and more, we are Evolution X!**


## First time installation:

**No need to flash the firmware separately, it is built-in**

 * Enter fastboot
 * Flash boot.img(recovery)
 * ### Code:
 * ```
   fastboot flash boot_ab boot.img
   ```
 * Boot to recovery (can do from bootloader or with buttons from power off state)
 * Now in recovery go to factory reset and confirm the reset
 * Reboot to recovery
 * Choose apply update and Apply from ADB
 * Now install Evolution zip via sideload
 * ### Code:
 * ```
   adb sideload Evolution.zip
   ```
 * Go back to main menu and reboot

## Update installation:

**Via recovery:**
 * Boot to recovery
 * Choose apply update and Apply from ADB
 * Now install Evolution zip via sideload and reboot 
 * ### Code:
 * ```
   adb sideload Evolution.zip
   ```
 * Go back to main menu and reboot to system


**Via OTA:**
 * Go to Settings -> System -> Updater and download latest build
 * Choose install and let it finish
 * If you have Magisk installed, don't click reboot when prompted and go to Magisk and choose install to inactive slot Reboot

**What's not working:**
 * You tell me

 **Downloads:**
 * [ROM](https://evolution-x.org/device/mars)
 * [boot-recovery](https://sourceforge.net/projects/evolution-x/files/mars/recovery)

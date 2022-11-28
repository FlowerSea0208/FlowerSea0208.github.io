---
title: Project Elixir 3.x for Mi 11 Pro (Mars/Star) and Mi 11 (Venus)
updated: 2022-10-30 23:43
---

![Elixir](https://s2.loli.net/2022/11/28/QoCrcBRPidvSuXp.jpg)

**Project Elixir is another aftermarket AOSP ROM which basically offers minimal UI enhancement & close to Stock Android ROM with great performance, security and stability. Most of the OEMs' these days will provide slow and untimely updates, but we don't do that here. We closely follow Google to bring the latest updates to our users, and even prolong support for devices that have been declared obsolete by OEMs. Our ROMs' source code is open-source, secure, stable, and outstanding. Your experience while using Project Elixir will be butter smooth without compromising the quality of the Android experience. In short, it's perfectly balanced between Great Performance, Security, stability, minimal UI & awesome features including pixel goodies So do not hesitate anymore, join us now and start enjoying the beauty of stock Android. Download and enjoy Project Elixir on your respective devices!**


# First time installation:

**No need to flash the firmware separately, it is built-in**

 * Enter fastboot
 * Flash recovery.img (**use any of the other available recovery**)
 * ### Code:
 * ```
   fastboot flash boot_ab recovery.img
   ```
 * Boot to recovery (can do from bootloader or with buttons from power off state)
 * Now in recovery go to factory reset and confirm the reset
 * Reboot to recovery
 * Choose apply update and Apply from ADB
 * Now install Elixir zip via sideload
 * ### Code:
 * ```
   adb sideload Elixir.zip
   ```
 * Go back to main menu and reboot to system

## Update installation:

**Via recovery:**
 * Boot to recovery
 * Choose apply update and Apply from ADB
 * Now install Elixir zip via sideload and reboot 
 * ### Code:
 * ```
   adb sideload Elixir.zip
   ```
 * Go back to main menu and reboot to system


**Via OTA:**
 * Go to Settings -> System -> Updater and download latest build
 * Choose install and let it finish
 * If you have Magisk installed, don't click reboot when prompted and go to Magisk and choose install to inactive slot Reboot

### What's not working:
 * You tell me

### Device Changelog:
 * [Mars](https://github.com/ProjectElixir-Devices/Changelogs/blob/tiramisu/venus.md)

 * [Venus](https://github.com/ProjectElixir-Devices/Changelogs/blob/tiramisu/mars.md)

## Downloads :

**mars/Star**
 * [Elixir-Mars](https://projectelixiros.com/device/mars)

**Venus**
 * [Elixir-Venus](https://projectelixiros.com/device/venus) 
# KernelSU/APatch Manager for Recovery Mode (mm)
A fork of https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode and https://github.com/Magisk-Modules-Repo/mm that enables the script to work with KernelSU and APatch

Easily manage your **APatch/KernelSU Modules** from a terminal session in your custom recovery! *(e.g. [TWRP](https://twrp.me/))*

Yes who said Magisk Manager for Recovery Mode Couldn't work with APatch/KernelSU, so i made this a reality

## Disclaimer
- I have no responsability if something on your phone breaks be aware.


## Features list
- Automatically fix modules.img (e2fsck -fy) or you can reset modules by deleting the img directly
- List installed modules
- Toggle
  - Core only mode ON
  - Core only mode OFF
  - Disable
  - Remove


## Prerequisite
- **APatch or KernelSU existing Installation**
- **TWRP** or another custom recovery with terminal session support

## Setup

### Initial Installation

Just download the script for your root solution and place it on the root of your sdcard, then on recovery chmod it for execution:
adb push mm(-ksu or -apatch) /sdcard/mm (you can copy the file direcltly with a file manager for simplicity or drag and drop it on a terminal)
chmod +x /sdcard/mm
cd /sdcard
./mm

### Updates
After the initial installation,   
If there wil be probably they will be in this repo, you just will have to replace the script on your /sdcard and chmod +x it again.

### Uninstall
Just delete the /sdcard/mm script


## Usage
1. Boot into your custom recovery *(e.g. [TWRP](https://twrp.me/))*
2. Open up a terminal session from within your custom recovery
3. Run the `*/mm` or `sh /sdcard/mm` command to start managing your modules. 
4. Simply follow the instructions/wizard, everything is interactive!

## Links to the current KernelSU/APatch Manager for Recovery Mode
After i will upload everything

## Links to the current Magisk Manager for Recovery Mode
**Current - Rikj000**
- [Source Code](https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode)
- [Developer](https://github.com/Rikj000)
- [Donate](https://www.buymeacoffee.com/Rikj000)

**Original - VR-25** *(Deprecated!)*
- [Source Code](https://github.com/VR-25/mm)
- [Developer](https://github.com/VR-25)
- [Donate](https://paypal.me/vr25xda)

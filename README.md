# Thinkpad-X2100-51nb-OpenCore-Hackintosh

![Thinkpad X2100 hackintosh OpenCore](/thinkpad-x2100.jpg)
![Thinkpad X2100 using Iphone as webcam wirelessly](/thinkpad-x2100-continuity.jpg)

## Current Specs

- Modified ThinkPad X2100 built by KK-Mod Shop with a 51nb motherboard 
- Now fitted with 5th batch motherboard from Jacky, with 3000x2000 display
- ThinkPad X201S Chassis with brand new plastics
- ~~51nb Internal Motherboard (Gen4 with USB-C support)~~ 51nb Internal Motherboard (Gen5 with USB-C support)
- ~~Quad-core i7-10150u CPU 4th Batch 51nb~~ Upgraded: Hexacore i7 10710u CPU 5th Batch 51nb (both are compatible)
- 32gb DDR4 Ram (supports up to 64gb)
- ~~12.6 inch 3:2 2880 x 1920 resolution display~~ Upgraded: 3000 x 2000 resolution display (both are compatible)
- 6 Cell genuine Lenovo battery

## Instructions

Full install guide is available in the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#stuck-on-eb-log-exitbs-start)

- Download the EFI
- Generate SMBIOS for ~~MacBookPro15,2~~ ~~MacBookPro16,1~~ MacBookPro15,4 and put the values in config.plist. 

Any questions please ask.

Alternativly, open the config.plist with [OpenCore Configurator](https://github.com/notiflux/OpenCore-Configurator) and generate the values automatically. Check coverage and make sure the serial IS NOT VALID if you want iMessage to work ;) I also recommend [Hackintool](https://github.com/headkaze/Hackintool), it's super helpful for mounting EFI files and debugging.



## Working

- [x] **Tested with macOS Catalina 10.15.6, macOS Big Sur 11.6, Monterey and Ventura**
- [x] **Wifi and Bluetooth with AX200 (I will soon be swapping to Broadcom BCM94360NG)**
- [x] **Sleep** Also lights up the native ThinkPad Moon icon! :) (debug with `sudo pmset -g`)
- [x] **Trackpoint**
- [x] **All mouse buttons and trackpad**
- [x] **iMessage**
- [x] **Airdrop**
- [x] **Continuity Camera (In Ventura)**
- [x] **USB-C**
- [x] **Audio speakers**
- [x] **Volume control buttons**
- [x] **Brightness Control function keys**
- [x] **NVMe m.2 support**
- [x] **Full hardware acceleration**
- [x] **Battery reading and charging recognition**
- [x] **USB Ports**
- [x] **Shutdown**
- [x] **Restart**
- [x] **SD Card Reader**
- [x] **Headphone jacks**

## Not working

- Fingerprint reader

## Please note

VooDooPS2 Controller kext is now downgraded to version 2.2.4. If you swap to MacBookPro16,1 you can use the latest VooDooPS2 controller, but video out over USB-C stops working. VooDooPS2 2.2.4 seems much smoother and nice to use with the trackpoint. If you experience any issues please let me know. For initial Bios setup, please copy the bios settings from here: https://github.com/xy-tech/X2100-BIOS-EC#instructions-to-update

## Credits

Thanks for your support, your help was crucial for my progress!

- [lulujyc](https://github.com/lulujyc/51nb-X210-Hackintosh) for helpful insights on the ThinkPad forums
- [Dortania](https://github.com/dortania) for this in depth OpenCore Desktop Guide
- [Acidanthera](https://github.com/acidanthera) So many quality Kexts!
- [OpenCore project](https://github.com/OpenCorePkg) So much better than Clover!
- [headkaze](https://github.com/headkaze) Hackintool

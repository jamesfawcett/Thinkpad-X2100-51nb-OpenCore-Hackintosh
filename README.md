# Thinkpad-X2100-51nb-OpenCore-Hackintosh

![Thinkpad X2100 hackintosh OpenCore](/thinkpad-x2100.jpg)

## Current Specs

- Modified ThinkPad X2100 built by KK-Mod Shop with a 51nb motherboard 
- ThinkPad X201s Chassis with brand new plastics
- 51nb Internal Motherboard (Gen4 with USB-C support)
- Quad-core i7-10150u CPU
- 32gb DDR4 Ram (supports up to 64gb)
- 12.6 inch 3:2 2880 x 1920 resolution display
- 6 Cell genuine Lenovo battery

## Instructions

Full install guide is available in the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#stuck-on-eb-log-exitbs-start)

- Download the EFI
- Generate SMBIOS for MacBookPro15,2 and put the values in config.plist. 

Alternativly, open the config.plist with [OpenCore Configurator](https://github.com/notiflux/OpenCore-Configurator) and generate the values automatically. Check coverage and make sure the serial IS NOT VALID if you want iMessage to work ;) I also recommend [Hackintool](https://github.com/headkaze/Hackintool), it's super helpful for mounting EFI files and debugging.

## Working

- [x] **Tested with macOS Catalina 10.15.6 and macOS Big Sur 11.6**
- [x] **Wifi and Bluetooth with AX200 (I will soon be swapping to Broadcom BCM94360NG)**
- [x] **Sleep** Also lights up the native ThinkPad Moon icon! :) (debug with `sudo pmset -g`)
- [x] **Trackpoint**
- [x] **All mouse buttons and trackpad**
- [x] **iMessage**
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

## Credits

Thanks for your support, your help was crucial for my progress!

- [lulujyc](https://github.com/lulujyc/51nb-X210-Hackintosh) for helpful insights on the ThinkPad forums
- [Dortania](https://github.com/dortania) for this in depth OpenCore Desktop Guide
- [Acidanthera](https://github.com/acidanthera) So many quality Kexts!
- [OpenCore project](https://github.com/OpenCorePkg) So much better than Clover!
- [headkaze](https://github.com/headkaze) Hackintool

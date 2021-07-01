# Thinkpad-X2100-51nb-OpenCore-Hackintosh


## Current Specs

- Modified ThinkPad X2100 built by KK-Mod Shop to a very high standard. It's perfect! 
- ThinkPad X201s Chassis with brand new plastics
- 51nb Internal Motherboard (Gen4 with USB-C support)
- Quad-core i7-10150u CPU
- 32gb DDR4 Ram (supports up to 64gb)
- 12.6 inch 3:2 2880 x 1920 resolution display
- 6 Cell genuine Lenovo battery

## Instructions

I will improve on this section if it is helpful? Please let me know! Full install guide is available in the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#stuck-on-eb-log-exitbs-start)

- Download the EFI
- Generate SMBIOS for MacBookPro15,2 and put the values in config.plist. 

Alternativly, open the config.plist with [OpenCore Configurator](https://github.com/notiflux/OpenCore-Configurator) and generate the values automatically. Check coverage and make sure the serial IS NOT VALID if you want iMessage to work ;) I also recommend [Hackintool](https://github.com/headkaze/Hackintool), it's super helpful for mounting EFI files and debugging.

## Working

- [x] **Tested with macOS Catalina 10.15.6 and macOS Big Sur**
- [x] **Wifi and Bluetooth with AX200 (I will soon be swapping to Broadcom BCM94360NG)**
- [x] **Trackpoint**
- [x] **iMessage**
- [x] **The three mouse buttons in front of trackpoint**
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


## Not working so far

- Two front left and right trackpad mouse buttons
- Sleep
- SD Card reader
- Fingerprint reader

## Credits

Thanks for your support, your help was crucial for my progress!

- [lulujyc] (https://github.com/lulujyc/51nb-X210-Hackintosh) for his insights and help
- [Dortania](https://github.com/dortania) for this in depth OpenCore Desktop Guide
- [Acidanthera](https://github.com/acidanthera) So many quality Kexts!
- [OpenCore project](https://github.com/OpenCorePkg) So much better than Clover!
- [headkaze](https://github.com/headkaze) Hackintool

# Asus Zenbook Hackintosh
Working Bootloader with all needed kext. Just copy the EFI folder into the USB drive with the macOS installer. After that, you should be able to  install macOS from the USB drive. More information in [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

![Screenshot](/screenshot.png?raw=true)

Tested on macOS Big Sur 11.6.6 and OpenCore 0.8.0

***Note:** this EFI does not support NVMe drives, to fix this use [NVMeFix Kext](https://github.com/acidanthera/NVMeFix)*

# Laptop Specifications

## *ASUS Zenbook UX333FN*
| Hardware                 | Name                                                     |
| ----------- | ----------------------------|
| CPU            | **Intel Core i5-8265U @ 1.60 GHz** |
| GPU    | **Intel UHD Graphics 620, NVIDIA MX150 (*disabled*)** |
| Memory | **8 GB LPDDR3** |
| Storage | **Intel 660P SSD** |
| Sound Card     | **Realtek ALC294** |
| Touchpad     | **ELAN1200 I2C HID** |
| WiFi Card     | **Intel Dual Band Wireless-AC 8265** |

#### What's working

- Trackpad
- Display Brightness
- Wifi and BT
- USB C
- Battery Monitoring
- Power Management
- Graphics Acceleration

#### Not Workling

- Keyboard Backlight
- Brightness Keys
- Sound

#### Untested

- HDMI
- iServices
- AirPlay, AirDrop

#### Based on
 [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

#### Credits

@acidanthera for OpenCore and the great guides.

@TheNewJavaman for his [EFI Folder](https://github.com/TheNewJavaman/asus-zenbook-ux433fn-hackintosh-opencore-efi)

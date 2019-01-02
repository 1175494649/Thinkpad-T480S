# macOS on Lenovo ThinkPad T480s

This repository contains the configuration to run macOS (Mojave `10.14`) on a Lenovo ThinkPad T480s laptop.

## Used Hardware Configuration

- Lenovo ThinkPad T480s
  - Intel i7-8550U
  - 8GB RAM onboard + 8GB Kingston DDR4 2400-SODIMM
  - WD Black 3D NVMe SSD 500G
  - Dell DW1560 Wireless (original Intel AC8265 not working)
  - Realtek ALC257
  - Intel UHD Graphics 620 (Nvidia MX150 disabled, Optimus not supported by macOS)
  - Power management and battery status by ACPI hotpatching
  - Integrated camera (works out of the box)
  - Keyboard/Elan Touchpad (PS/2) using `ApplePS2SmartTouchPad.kext` v4.7b5 by EMlyDinEsH
    - Support multi-touch gestures
    - Need to disable Trackpoint in BIOS (otherwise touchpad would be disconnected)
    
- Disabled devices
  - WWAN (no module)
  - Trackpoint
  
- Untested devices
  - SD card reader
  - Fingerprint scanner
  - Thunderbolt 3 (USB type-c works)
  
- Firmware Revisions
  - BIOS version `1.27`


## Credits

- [linusyang92/macOS-ThinkPad-T480s](https://github.com/linusyang92/macOS-ThinkPad-T480s)

# MacOS ThinkPad T440/T440s

Hackintosh MacOS Catalina 10.15.x

## Pre-Installation

### 1. Warning: check you BIOS version

**You should update(downgrade) BIOS to v2.36 or MOD BIOS to remove Wireless Whitelist!**

### 2. BIOS settings

| Item | Setting |
| ------------- | ------------ |
| Security Chip | Disabled |
| Memory Protection Execution Prevention | Enabled |
| Virtualization | Enabled |
| Fingerprint Reader | Disabled |
| Anti Theft | Disabled |
| Computrace | Disabled |
| Secure Boot | Disabled |
| Startup Network Boot | PCI LAN |
| UEFI/Legacy Boot | UEFI Only |
| CSM Support | Yes |
| Boot Mode | Quick |


### 3. Hardware

|Compenent|Reference|
|---|---|
|CPU|Intel Core i5-4300U vPro|
|RAM|DDR3L 8GB Bus 1600MHz|
|GFX|Intel HD Graphics 4400|
|Sound|Realtek ALC292|
|Display|14" IPS LCD|
|WIFI|Intel(R) Dual Band Wireless-AC 7260|

#### What will work

- Power Management (C/P-States, Fan RPM, Speedstep, etc)
- HD Intel Graphic Card (HD4400)
- Sleep (Sleep from menu + lid close sleep)
- Camera
- Ethernet
- Battery Status
- Brightness
- Keyboard, Trackpad and Trackpoint
- Sound (automatic headphone detection, mute, volume controls fully working)
- USB Ports
- SD Card Reader
- Bluetooth

#### Not working

- Fingerprint Reader
- VGA

#### WIFI

Inbuilt Intel WiFi won't work out of the box.

- BCM94360CSAX (Recommend)
- DW1560 (BCM9435Z) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz
- DW1830 (BCM943602BAED) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz
- DW1820A (BCM94350ZAE) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz (Broadcom)

## Installation

....

## Post-Installation


### 1. Tools needed

- Clover Bootloader

### 2. Kexts used

- ACPIBatteryManager.kext
- AppleALC.kext
- EFICheckDisabler.kext
- FakeSMC.kext
- IntelMausi.kext
- Lilu.kext
- USBPorts.kext
- VoodooPS2Controller.kext
- VoodooInput.kext
- VoodooSDHC.kext
- WhateverGreen.kext

### 3. Patched

- Copy patch to /ACPI/patched/

## Issue:

- None

## Support me

- Paypal: <https://www.paypal.me/thebinhluong0519>
- Ethereum: 0xC202255193D95979A7C937aA3CB5220FAD9E2aBe

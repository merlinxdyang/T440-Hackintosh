# MacOS ThinkPad T440/T440s

MacOS Catalina on ThinkPad T440/T440s

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
| Secure Boot | Disabled |
| UEFI/Legacy Boot | UEFI Only |
| CSM Support | No |
| Boot Mode | Quick |


### 3. Configuration

| Specifications      | Detail                                      |
| ------------------- | ------------------------------------------- |
| Processor           | Intel Core i5-4300U                         |
| Memory              | Samsung DDR3L 8GB Bus 1600MHz               |
| Hard Disk           | Samsung SSD P851                            |
| Integrated Graphics | Intel HD Graphics 4400                      |
| Monitor             | AUO B140HAN01.3 FHD IPS 1920x1080           |
| Sound Card          | Realtek ALC292                              |
| Wireless Card       | Intel Dual Band Wireless-AC 7260            |

### 4. Current Status

#### What will work

- Intel HD 4400 Graphics QE/CI
- USB Ports
- Intel Ethernet
- Audio (All Inputs & Outputs)
- Sleep and Wake
- Mini DisplayPort and Mini DisplayPort Audio
- CPU and IGPU Power Management
- Battery Status
- Brightness
- Function Keys (Fn)
- ClickPad and TrackPad
- Integrated Camera

#### Not working

- Fingerprint Reader
- VGA

### 5. Wireless Card Replace

Inbuilt Intel Wi-Fi won't work out of the box.

- BCM94360CSAX (Recommend)
- DW1560 (BCM9435Z) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz
- DW1830 (BCM943602BAED) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz
- DW1820A (BCM94350ZAE) - 802.11a/b/g/n/ac 2.4 GHz & 5 GHz (Broadcom)

## Installation

### 1. Tools needed

- Clover Bootloader
- OpenCore Bootloader

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

- PayPal: <https://www.paypal.me/thebinhluong0519>
- Ethereum: 0xC202255193D95979A7C937aA3CB5220FAD9E2aBe

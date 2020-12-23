# Hackintosh-ASUS-PN62

This is the hackintosh based on OpenCore bootloader for [ASUS Mini PC PN62](https://www.asus.com/us/Mini-PCs/Mini-PC-PN62/)

![Hackintosh](misc/pn62.png)

![Hackintosh](misc/macver.png)

Current Bootloader: [OpenCore 0.6.4](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.4)

## Hardware:
| Component | Details |
|--------------|------------------------------------------------------------------------------------------------------------------|
| CPU | [Intel® Core™ i7-10510U](https://ark.intel.com/content/www/us/en/ark/products/196449/intel-core-i7-10510u-processor-8m-cache-up-to-4-90-ghz.html)|
| iGPU | Intel® UHD Graphics |
| RAM  | 2x16GB 2666MHz DDR4 |
| Ethernet | [Intel® I219-V](https://ark.intel.com/content/www/us/en/ark/products/82186/intel-ethernet-connection-i219-v.html)|
| Wireless / BT | [Intel® Wi-Fi 6 AX201 + Bluetooth® 5.1](https://www.intel.com/content/www/us/en/products/docs/wireless/wi-fi-6-ax201-module-brief.html?wapkw=ax201) |
| Sound card | Realtek® ALC3236-VB2/ALC255 |
| SSD | [Samsung SSD 970 PRO 512GB](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-970-pro-nvme-m2-512gb-mz-v7p512bw/#) |
| HDD | [HGST HTS541010A7E630 1TB](https://www.hdsentinel.com/storageinfo_details.php?lang=en&model=HITACHI%20HTS541010A7E630)|
| Card Reader | Realtek® RTS5129 |
| SMBIOS | [MacMini 8,1](https://support.apple.com/kb/SP782?viewlocale=en_US&locale=en_US) |
--------

## Bios Settings:

## Kexts:
| Kext | Version |
| ------------ | ------------- |
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm/releases) | 1.1.0
[AppleALC](https://github.com/acidanthera/AppleALC/releases) | 1.5.5 |
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend/releases) | 1.2.2
[CtlnaAHCIPort](https://github.com/dortania/OpenCore-Install-Guide/blob/master/extra-files/CtlnaAHCIPort.kext.zip) | -
[FakePCIID_Intel_HDMI_Audio](https://bitbucket.org/RehabMan/os-x-fake-pci-id/downloads/) | 1027
[FakePCIID](https://bitbucket.org/RehabMan/os-x-fake-pci-id/downloads/) | 1027
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases) | 1.1.2
[IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases) | 1.1.2
[IntelMausi](https://github.com/acidanthera/IntelMausi/releases) | 1.0.4 |
[Lilu](https://github.com/acidanthera/Lilu/releases) | 1.5.0 |
[NVMeFix](https://github.com/acidanthera/NVMeFix/releases) | 1.0.4 |
[SMCProcessor](https://github.com/acidanthera/VirtualSMC/releases) | 1.1.9 |
[SMCSuperIO](https://github.com/acidanthera/VirtualSMC/releases) | 1.1.9 |
[USBMap](https://github.com/corpnewt/USBMap) | -
[VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases) | 1.1.9 |
[WhateverGreen](https://github.com/acidanthera/whatevergreen/releases) | 1.4.5 |

## Benchmarks:
### Disk Speed Test + Geekbench
![Hackintosh](misc/benchmark.png)
### Videoproc
![Hackintosh](misc/videoproc.png)
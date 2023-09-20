# Rayzen-iGPU-B450-hackintosh
OpenCore EFI for B450 Chipset Motherboard with AMD Ryzen 6 cores with iGPU
WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**
|  Components             |         Requirements                |            Note                      |
|-------------------------|-------------------------------------|--------------------------------------|
| CPU                     |  6 cores AMD CPU                  |  This EFI is using a 6 cores kernel patch. If your CPU have more or less cores than this EFI, change it and refer to the OpenCore guide. |
| GPU                     |  AMD Vegas iGPU        | Thanks to NootedRed to get AMD iGPU support on this Hackintosh! Make sure that you don't have a dGPU in your system! |
| Motherboard             | B450 motherboards            |  This build will only work for the B450 motherboards, for other, please refer to the OpenCore Guide.|
| RAM                     | 2 x 16GB + 8GB DDR4 3200Mhz  |  |
| Ethernet  | Realtek RTL8111 Gigabit Ethernet |  |
| Audio     | Realtek ALC892 | |
| OS | macOS Ventura 13.5 | |

## Settings to change

|BIOS Settings|Toggle|
|-------------------------|-------------------------------------|
|Secure Boot|**OFF**|
|TPM|**OFF** (optional)|
|Above 4G Decoding|**ON**|
|VRAM for iGPU|Above 512M for best results|
|Fast Boot|**OFF**|
|CSM|**OFF**|
|Serial Port|**OFF**|

## Whats Work?

- CPU Power Management
- Shutdown , Restart and Sleep
- Ethernet
- Bluetooth
- HDMI
- Audio (Rear & Front)
- TRIM Support for SSD
- Etc

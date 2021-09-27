# Hackintosh OpenCore EFI for Gigabyte B550I Aorus Pro AX

![Screen Shot 2021-09-28 at 00 43 53](https://user-images.githubusercontent.com/28827754/134966538-90e1a201-1905-43a6-b78c-37412ee273d1.png)

This repository provides the basic EFI folder to run macOS Big Sur Version 11.6 (Build 20G165) on Gigabyte B550I Aorus Pro AX motherboard. The default provided currently using a Ryzen 5 3600 6 Cores CPU and a Dell AMD Radeon RX550 (Lexa Chipset). This is intended as a reference and to share improvements for similar build, not as an out of the box EFI to download.
It is highly recommended to start with a vanilla OpenCore and following OpenCore Vanilla Guide first.

Specification :
- CPU: AMD Ryzen 5 3600 @ 3.6GHz
- Motherboard:	Gigabyte B550i Aorus Pro AX
- RAM: 16GB (2 x 8GB) Corsair LPX @ 3200MHz @OC 3600MHz C18
- Audio: Chipset	ALCS-1200A
- GPU: Dell AMD's Lexa RX 550 4GB
- WiFi & Bluetooth:	Intel® Wi-Fi 6 AX200
- Lan: Intel® I225-V 2.5Gb Ethernet
- OS Storage:	NVMe ADATA SX8200 Pro 256GB
- Bank Storage:	NVMe Micron MTFDHBA512QFD 512GB
- CPU Cooler:	Cryorig C7G-Noctua NFA9x14
- Case:	ZS-Case A4DC V2 Volume 4.4 Liters
- PSU: Flex U1 600W Platinum
- OpenCore: 0.6.2
- MacOS: 10.16

What works:

    Audio (alcid=3)
    Ethernet
    USB
    Wi-Fi
    Bluetooth
    iMessage, FaceTime

Known issues:

    Partially-working virtualization (only VirtualBox & Parallels Dekstop 13.1.0 or below)
    3.5mm Jack microphone (haven't tested)

Credits

    everyone developing for the hackintosh community
    the dortania team

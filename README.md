# Novus-Hackintosh
OpenCore for MacOS Sonoma on my machine

### Specifications
```
CPU          : AMD Ryzen 5 7600 3.8 GHz 6-Core Processor
Motherboard  : MSI PRO A620M-E Micro ATX AM5 Motherboard
Memory       : G.Skill Ripjaws S5 32 GB (2 x 16 GB) DDR5-6000 CL30 Memory
Storage      : Western Digital Blue SN570 1 TB M.2-2280 PCIe 3.0 X4 NVME Solid State Drive
Video Card   : Asus DUAL OC Radeon RX 6750 XT 12 GB Video Card
Power Supply : Gigabyte P750GM 750 W 80+ Gold Certified Fully Modular ATX Power Supply
Monitor      : LG 24.0" 1920 x 1080 75Hz Monitor
```

### Kexts
- AppleALC - For audio<br>
- AppleMCEReporterDisable - Memory module not setup error fix<br>
- [NootRX](https://github.com/ChefKissInc/NootRX) - Graphics driver for 6750XT card instead of WhateverGreen<br>
- NVMeFix - Patches of NVMe storage driver<br>
- USBMap - Custom patch for mapping the USB ports correctly<br>
- Lilu, Virtual SMC, RealtekRTL8111, RestrictEvents - Required ones for basic functionalities<br>

### Screenshots
![Screenshot 1](/Screenshots/ss_1.png)
![Screenshot 2](/Screenshots/ss_2.png)

### What isn't working
- Sleep - Likely caused by Graphics driver or port stuff
- Bluetooth - Could potentially be fixed
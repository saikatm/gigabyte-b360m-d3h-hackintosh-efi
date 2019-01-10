



Hackintosh Mojave Installation Guide for Gigabyte B360M D3H Hackintosh & Clover EFI Folder 

### My System Hardware
![About My Mac]()(about-mac.png)

- CPU: Intel i3 8100 
- Motherboard: Gigabyte B360M-D3H 
- Memory: G.Skill DDR4 8GB x 2 
- GPU: Sapphire Radeon RX 560 4GB

### What's Working?
Almost Everything.

##### Working
- Ethernet
- Audio (including digital audio)
- Sleep/Wake 
- iGPU + RX 560 GPU
- All USB ports (including USB 3)
- App Store

### Install Guide
I made the installer on Windows using Olarila Mojave image & used [Etcher.app]()
Download Olarila Image From the Forum with Installation Guide:
[http://olarila.com/forum/viewtopic.php?f=51&t=6743]()

Or You can Use a [Vanilla Guide]() but Olarila is faster but both are Vanilla. (olarila is highly recommended) 

After Installing MacOS on your system copy my clover folder to your EFI Partition and Open the config.plist make sure you set the following:
- SerialNumber
- BoardSerialNumber
- SmUUID

**Also Depending on your CPU Choose the Right SMBIOS.**

### Bios Settings: 
•	Load optimised default 
•	Disable CSM 
•	Disable Fast 
•	Enable Internal Graphics & VT-D 
•	Disable only serial port (first option) 

### Post Installation
Fix USB 3 Ports
[How to Stay within 15 ports limit using UsbInjectall and Clover boot argument]()

\<del\>Sound\</del\> (ALC892)
_Sound should be working obb if you use my clover folder._



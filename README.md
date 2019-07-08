# My Github Page for Clover Folder

Hackintosh Mojave Installation Guide for Gigabyte B360M D3H Hackintosh & Clover EFI Folder

⚠️  **Please Read the whole readme file for better understanding. Also I will share some tips and tricks.**

## **My  Hardware**

- **CPU**: Intel i3 8100
- **GPU**: Sapphire Radeon RX 560 4GB
- **Motherboard**: Gigabyte B360M-D3H

### **What's Working?**

- Sleep/Wake
- Ethernet
- Audio ALC892 (native AppleALC audio)
- iGPU Quick Sync + RX 560 GPU
- All USB ports (USB 2 + USB 3)

    ![](about.png)

### **Install Guide**

- [Olarila Installation](https://olarila.com/forum/viewforum.php?f=50) (easy and noob friendly)

OR

- [Vanilla Installation](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/) (hard for beginners)

### Pre-Installation

I made the installer on Windows using **Olarila** Mojave image & used [Etcher.app](https://www.balena.io/etcher/) Download Olarila Image From the Forum with [Installation Guide](http://olarila.com/forum/viewtopic.php?f=51&t=6743): Or You can Use a Vanilla Guide but Olarila is faster but both are Vanilla. (***Olarila is highly recommended***)

### First Proper BIOS Setting is needed for the macOS to boot:

- Load optimised default
- Disable CSM
- Disable Fast
- Enable Internal Graphics & VT-D
- Disable only serial port (first option)

Now **Read The More Detailed Installation Guide [Here](https://olarila.com/forum/viewtopic.php?f=50&t=8685).** *(as re-writing the same thing is waste of time)*

### Post Installation

After Installing MacOS on your system copy my clover folder to your EFI Partition and Open the config.plist make sure you do the following:

- Set SMBIOS to **iMAC 18'2** or **iMAC 19'2** for i3-8100 (*Depending on your CPU Choose the Right SMBIOS)*
- Get a Patched DSDT.aml for your hackintosh from [Olarila Forum](https://olarila.com/forum/viewtopic.php?t=6401) (Must Needed for a stable and working hackintosh)
- Update the Kext to the latest version
- Generate  in Clover Configurator: **SerialNumberBoard, SerialNumber, SmUUID**

**💡 The Setup is 100% Stable! I have never faced any kernel panic or reboot.**

### Post Installation Tips

## Links:

 [How to Stay within 15 ports limit using UsbInjectall and Clover boot argument](https://olarila.com/forum/viewtopic.php?f=79&t=7370&fbclid=IwAR0aba59fTABiOx2hLesroLLHOTl8rAQQwQ-d0bpPm4LZ3UNovBrGdjyEb8)
[[Guide] Easy Audio Solution with AppleAlc](https://olarila.com/forum/viewtopic.php?f=28&t=9788)
[HACKINTOSH IMESSAGE + ICLOUD + FACETIME REPAIR GUIDE](https://hackintosher.com/guides/quick-fixes-facetime-icloud-imessage-hackintosh-not-working/)
[Hide Volumes / Extra Boot Entries With Clover Config](https://olarila.com/forum/viewtopic.php?f=28&t=7451#p66199)


### Screenshots

![Quick Sync](quicsync.png)
![Audio](/Screenshots/audio.png)
![Ethernet](/Screenshots/ethernet.png)
![Graphics](/Screenshots/graphics.png)
![USB 3](/Screenshots/usb.png)

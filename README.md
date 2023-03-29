# Multiboot-Yumi-and-Ventoy
Error 'boot.img not found' when Ventoy2Disk.exe is placed in Yumi-directory.

**HowTo Create Multiboot-USB for Windows:**

1. Create directory c:\\users\\your_username\\documents\\portable\\multiboot\\ventoy
2. Create directory c:\\users\\your_username\\documents\\portable\\multiboot\\yumi\\
3. [Download Yumi 1.0.1.5](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/), unpack files to .....\\multiboot\\yumi\\
4. [Download Ventoy 1.0.90](https://github.com/ventoy/Ventoy/releases/download/v1.0.90/ventoy-1.0.90-windows.zip), unpack files to .....\\multiboot\\ventoy\\
5. Copy Ventoy2Disk.exe to c:\\users\\your_username\\documents\\portable\\multiboot\\yumi\\ 
6. Start YUMI-exFAT-1.0.1.5.exe
7. Teying to install an App, not verified by Microsoft.  Install Yet?
8. App unknown distributor. Edit on your device? Yes.
9. License agreement. I agree.
10. Select driveletter USB-device. Mostly: D: (disk 1) YUMI
11. Do you want Yumi to prepare and format it? Yes.
12. Create Ventoy based Yumi USB. OK.
13. Error in log.txt: boot.img not found. Please, run under the correct directory.


# How to Install EasyDIS v44 Based on DIS v44 and GT1 for BMW Diagnostics
 
EasyDIS v44 is a software package that allows you to run BMW DIS v44 and GT1 programs on your laptop using a virtual machine. DIS v44 and GT1 are diagnostic tools that can communicate with BMW vehicles and perform various functions such as reading fault codes, clearing adaptations, coding modules, etc. In this article, we will show you how to install EasyDIS v44 step by step using VMware and Daemon Tools.
 
**Download » [https://t.co/DVwt702oeC](https://t.co/DVwt702oeC)**


 
## Requirements
 
- A laptop running Windows, preferably XP SP2.
- A USB-OBD cable (or a serial-OBD cable if your laptop has a serial port).
- INPA / EDIABAS.
- VMware version 5.5 or later.
- EasyDIS-base-44-v1.0.iso and GT1\_v44\_programs.iso.
- Diag Head Emulator.

## Installation Procedure

1. Disable Windows Firewall and Anti Virus.
2. Install drivers for your USB-OBD cable and USB-serial adapter, making sure it is set as port COM1.
3. Install / update INPA / EDIABAS, using ADS interface, not OBD.
4. Change environment path in Windows to c:/ediabas/bin.
5. Install ADS Setup.
6. Install OBD setup.
7. Edit ediabas.ini, change remote-host and port.
8. Install VMware [version 5.5 or higher].
9. Edit VMware network bridge in network editor.
10. Set up the new virtual machine with ethernet set to the network bridge.
11. Install Diag Head Emulator.
12. Mount âEasyDIS-base-44-v1.0â in Daemon Tools.
13. Edit the CD drive of your virtual machine to use the Daemon Tools drive (F: in this case).
14. Start the virtual machine and quickly press F2 to enter the BIOS for it.
15. Set the CD-Rom to be the first boot device.
16. Save and exit the BIOS. The computer will reboot. The installation of GT1 begins[^1^].
17. The installation ends and you are notified to eject the CD, and restart the VM, but do not do that yet!!
18. Eject the iso from Daemon Tools.
19. Mount the file âGT1\_v44\_programsâ in Daemon Tools.
20. Now Shut-Off the Virtual Machine, and Restart it.
21. Return to the BIOS by pressing F2 and set the boot order back to default.
22. Save and Exit, and the VM will boot up.
23. The following screen will appear, select your language and vehicle, press the green arrow to continue[^2^].
24. Select your country, and enter 12345 for dealer number. The rest of the info you can make-up[^2^].
25. Once you have entered the required information, click End > Quit[^2^].

Congratulations! You have successfully installed EasyDIS v44 based on DIS v44 and GT1. You can now use these programs to diagnose your BMW vehicle. To run DIS or GT1, you need to load DIS, open/run Diag Head and open IFHsrv32.exe[^1^]. Make sure you calibrate the touch shield and connect the diagnostic head in the administration menu[^1^]. You also need to connect your USB-OBD cable or serial-OBD cable to your vehicle's OBD port and your laptop's USB port or serial port. Enjoy!
 8cf37b1e13
 

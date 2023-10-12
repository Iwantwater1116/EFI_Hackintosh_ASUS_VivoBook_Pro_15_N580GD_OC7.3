# EFI_Hackintosh_ASUS_VivoBook_Pro_15_N580GD_OC 0.93
Hackintosh On ASUS Vivobook Pro 15 N580GD OC 0.93

Last Words:
====================================================

2023/10/12
Aside from my own purchase of an official Mac computer, there is no longer a need for a Hackintosh. The latest macOS 14.0 Sonoma now supports a minimum of MacBook Pro 2018 and later models. It is anticipated that in the future, the N580GD may no longer be able to update to the latest macOS. Consequently, OpenCore Bootloader updates for the N580GD will no longer be provided.

A few days ago, I successfully installed the latest macOS 14.0 Sonoma on the N580GD, and it can boot smoothly, just like Ventura. However, I lost the bootloader before I had a chance to upload it. The method I used involves updating my current OpenCore bootloader, which supports Ventura, to the latest OpenCore version. Additionally, updating the airportitlwm.kext and IntelBluetoothFirmware.kext to the Sonoma version is necessary for a smooth boot. Currently, IntelBluetoothFirmware.kext has a Sonoma version available, but the Sonoma version of airportitlwm.kext has not been released yet. You can patiently await its release or search on Github for information about airportitlwm.kext and test drivers created for Sonoma Beta.

Finally, I want to express my gratitude for all your support. In the future, I will no longer be providing updates. If anyone wishes to continue maintaining this project, please let me know, and I will gladly hand over the project for them to maintain.


Notebook Specification:
=====================================================
Name: ASUS Vivobook Pro 15 N580GD 
CPU:  Intel i7-8750H
RAM:  16GB DDR4
GPU:  Nvidia 1050 4GB
IGPU: Intel Graphics UHD 630
Display: IPS Monitor 15.6 inch

What's Working:
=====================================================
1.  IGPU
2.  TouchPad
3.  Wifi
4.  Bluetooth
5.  Sleep
6.  All USB Port
7.  Ethernet
8.  HDMI and HDMI Audio(Can't adjust volume and have some bug when waked)
9.  Display Port and Display Port Audio (Can't adjust volume and have some bug when waked)
10. 3.5mm audio
11. Keyboard Backlight Adjustment
12. SD Card Reader
13. Logitech Bluetooth Mouse And Keyboard connect
14. Android USE Ethernet (HORNIDS)


What's not Working:
=====================================================
1. Nvidia GPU

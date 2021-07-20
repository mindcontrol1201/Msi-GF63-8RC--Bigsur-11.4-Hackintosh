# Msi-GF63-8RC--Bigsur-11.4
!!!Note!!! Generate your own serial numbers using Macbook pro 15,1 Symbios !!!

Successfully installed macOS Bigger 11.4 on MSI GF63 8RC laptop. Dual booted along with windows on same SSD.
Hardware:
CPU: i5-8300H
GPU: iGPU (Intel UHD Graphics 630), Nvidia GTX 1050 4gb (disabled)
RAM: 16 GB (stock)
Motherboard Model/Laptop Model: MS-16R3 (U3E1) / MSI GF63 8RC
WiFi/BT: Intel Wireless-AC 9560 (WiFi working with Airportitlwm )
Ethernet: RealTek Gigabit Ethernet
Audio: Built in, ALC 269-VC (Fully working with AppleALC, layout-id: 6)
Touchpad: Stock I2C-HID touchpad
Currently Dual booted with Windows 10 on same disk, booting Mac OS from Usb Stick.
Working:
- iGPU
- CPU Power Management
- Audio + stock microphone
- WiFi
- Ethernet
- all USB-ports and headphone jack
- Touchpad
- Battery Indicator
-Bluetooth
-USB Sidecar
-Iservices
-HDMI
- few handoff featues

- Not Working:
- Bluetooth Mic and airdrop( Fix- use Latest beta intelbluetooth kext)
- Brightness control keys (Brightness can be controlled from settings)
-Wifi doesn’t work after immediate reboot from windows. ( Fix- If you have a dual-boot machine with a recent version of Windows and start seeing problems during initialization of the WiFi device when booting Linux, the problem could be due to the “fast startup” feature on Windows.With this feature enabled, Windows don't really shut down the entire system, but leaves things partially running so you can start the machine faster again. Try to disable this option, on Windows 10 it should be in “Control Panel→Hardware and Sound→Power Options→System Settings”. Select “Chooose what the power buttons do” to access the System Settings from the Power Options. Then disable the “Fast Startup” option in “Shutdown Settings”. This will cause Windows to fully shutdown and may solve the issue.)

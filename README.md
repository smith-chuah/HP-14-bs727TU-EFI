# HP-14-bs727TU-EFI
My Hackintosh EFI file for the HP 14 bs727TU.

This is the EFI file for the HP 14 bs727TU from 2017/18 which I used to successfully boot (up to) Ventura on my device. Keep in mind that the files do not include the WiFi/Bluetooth kext as this device does not have a compatible internet card. I have also removed the HDMI output & USB mapping kext as that might differ across devices, please refer to the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).

Stuff that works
* Display
* Graphics acceleration
* Ethernet
* HDMI
* Sleep/wake
* Sound + mic
* Keyboard + touchpad + webcam
* USB
* basically almost everything (even the disk drive)
Things that don't work
* Wi-Fi and Bluetooth (unsupported chip, too broke and lazy to find a proper replacement/dongle)

![Image 17-05-2025 at 12 42 PM](https://github.com/user-attachments/assets/172c2cc4-2b63-477c-a09d-083cbefbb075)

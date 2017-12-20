# LykenNS
This is a raspberry pi disk image made especially for the RPI Zero W.

# Products You Need

Raspberry Pi Zero W:  
https://www.amazon.com/Raspberry-Pi-Zero-Wireless-Essentials/dp/B06XCYGP27/

Panda Wireless Network Adapter:  
https://www.amazon.com/Panda-300Mbps-Wireless-USB-Adapter/dp/B00EQT0YK2/

64 GB Micro SD Card or Higher for more storage
https://www.amazon.com/Samsung-MicroSDXC-Adapter-MB-ME64GA-AM/dp/B06XX29S9Q/

Make sure you have a good MicroUSB charger.

# How to install
[Software]
1. Download the program Win32 Disk Imager or Etcher
Etcher: https://etcher.io/
Win32DiskImager: https://sourceforge.net/projects/win32diskimager/

2. Download the Disk Image from this repository

3. In Win32 Disk Imager or Etcher select the Disk Image and then select the device.

4. Click write.

[Hardware]

1. Put the formatted sd card into the RPI

2. Put the wireless adapter into the micro usb to usb adapter.

3. Plug the RPI into the power source.

4. Wait a couple of minutes for the RPI to boot

5. On your computer intall VNC Viewer: https://www.realvnc.com/en/connect/download/viewer/

6. After installed connect to the Pi's wifi network with SSID: LykenNAS Password: lykenfile

7. Go onto VNC Viewer once connected

8. Add host 169.254.243.136 Username: pi Password: lykenfile

9. Once you are in go to the top right corner and select wifi then use wlan1 and connect to your network.

10. Now you can disconnect and test the pi by going to the adress 192.168.1.200

11. You are done! Now you can type the adress 192.168.1.200 in the url bar and use the server like that.

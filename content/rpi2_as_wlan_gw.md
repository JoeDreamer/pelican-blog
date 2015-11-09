Title: Finished setting up Raspberry Pi 2 set up as a WLAN gateway
Date: 2015-11-06 09:46
Tags: rpi, wlan
Category: Raspberry Pi 
Author: JoeDreamer
Summary: RPi2 as WLAN gateway

Finally, I have finished setting up my Raspberry Pi 2 as a WLAN gateway.

I did configurations mostly based on
[these instructions](https://learn.adafruit.com/downloads/pdf/setting-up-a-raspberry-pi-as-a-wifi-access-point.pdf),
but with several information specific to my Wi-Fi dongle from the following web
sites:

1. Custom modules for RealTek 8192cu Usb Wifi Dongle
	- <http://wannabe-nerd.tweakblogs.net/blog/10870/wifi-access-point-using-a-realtek-8192cu-based-usb-wifi-dongle-with-a-raspberry-pi.html>
	- <https://bogeskov.dk/UsbAccessPoint.html>
2. [Installation of kernel source](https://getpocket.com/redirect?url=https%3A%2F%2Fgithub.com%2Fnotro%2Frpi-source%2Fwiki)
3. [Setting up NAT using ufw](https://getpocket.com/redirect?url=https%3A%2F%2Fforum.manjaro.org%2Findex.php%3Ftopic%3D1371.0)

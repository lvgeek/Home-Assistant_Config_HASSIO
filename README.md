
I'm currently running Home Assistant version 0.59.2. 
My preferred installation method is Hassio on a RPi3.

After downloading the disk image and writing it to an SD card with Etcher

INSTALLING HASS.IO
1. Put the SD card in your SD card reader
2. Open Etcher, select the Hass.io image and flash it to the SD card.
3. WiFi setup only: open the file system-connections/resin-sample with a text editor. Change ssid to be your network name and psk to be your password.
4. Unmount the SD card and remove it from your SD card reader.
5. Insert the SD card into your Raspberry Pi 3. If you are going to use an Ethernet cable to supply Internet, connect that too.
6. Connect your Raspberry Pi to the power supply so it turns on.
7. The Raspberry Pi will now boot up, connect to the Internet and download the latest version of Home Assistant. This will take about 20 minutes.
8. Home Assistant will be available at http://hassio.local:8123.

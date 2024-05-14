# rpi-setup
Instructions for setting up the Rasberry Pi.
This has been tested on a Raspberry Pi 5, but will most likely run on some other models as well.

### Easy setup (Not currently available)
1. Boot the Raspberry Pi with the image in this repository.
2. Connect the Raspberry Pi to the internet.
3. Start the Raspberry Pi up, the web interface should be running at: ´http://ip-address:5000/´, ip-address being that of the Raspberry Pi.

### Manual setup
1. Boot Raspberry Pi OS to the Raspberry Pi. [Guide](https://github.com/raspberrypi/documentation/blob/develop/documentation/asciidoc/computers/getting-started/setting-up.adoc)
2. Connect the Raspberry Pi to the internet.
3. Install pynanovna with ´pip install pynanovna´.
4. Clone the repository [picc-device](https://github.com/PICC-Group/picc-device) and run the setup.py file with ´setup.py´.
5. Restart the Raspberry Pi.
6. The web interface should be running at: ´http://ip-address:5000/´, ip-address being that of the Raspberry Pi.

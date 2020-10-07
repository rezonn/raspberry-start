# raspberry-start
## MacOS
* Install [Raspberry Pi Imager](https://www.raspberrypi.org/downloads/)
* Select recommendend image, select SD card, flash
* Unplug and plug SD card
* Copy "wpa_supplicant.conf" (*replace SSID and pasword in file*) and "ssh" to sd card
## Pi
* Insert SD
* connect to power
## MacOS terminal
* Type (replace IP) *1
```
ssh pi@192.168.1.6
```
* Use password "raspberry"
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install nodejs npm
sudo apt-get install xrdp
```
* Use [Microsoft RDP](https://apps.apple.com/ru/app/microsoft-remote-desktop)
## Notes
*1 - Host key verification failed? 
```
cd .ssh
rm known_hosts
```

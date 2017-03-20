# pi-zero-particle-sensor
AWS Iot connection for SDS011 data from Raspberry Pi Zero W

## setup
install [dietpi](http://dietpi.com/) on sd card

for headless setup:
- Locate the file called dietpi.txt on sd card and edit it
- Set Wifi_Enabled=1.
- Enter your ssid Wifi_SSID=MySSID and Wifi_KEY=MyWifiKey (both are case sensitive).

ssh to pi
```bash
apt-get install python
apt-get install python-serial
```

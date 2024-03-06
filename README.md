# bash-script-for-copter

## guide

```bash
chmod +x ./script
./script
```

## text for nano
**/etc/dhcpcd.conf**
delete text
```conf
 interface wlan0
 static ip_address=192.168.11.1/24
```
/etc/wpa_supplicant/wpa_supplicant.conf 
past 
```
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
country=GB

network={
ssid="SSID"
psk="password"
 }
```

# RaspberryPi as Access Point (OpenWrt)
## Access Point configuration
![App Screenshot](https://github.com/ZakariyaaEddaaf/openwrt-access-point/blob/main/screenshot/network.png?raw=true)

configuration files:
+ /etc/config/network
+ /etc/config/wireless
+ /etc/config/dhcp
+ /etc/config/firewall

cp files inside config folder to overwite default configuration files
```
/etc/config
```

Issue: network need to be restarted !
```
/etc/init.d/network restart
ifconfig
```
## Zerotier

```
opkg update
opkg install zerotier
```


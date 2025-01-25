# Bypassing_MAC_adress_authentification
Ethical Hacking - BYPASS MAC AUTHENTIFICATION

* `MAC` : Media Acces Control
*  Address unique
* six pairs in hexadecimal (0 to 9 letters between A and F)
* usually appears as 00:50:56:CD:00:01
* physical address
* use to identify users

```bash
iwconfig
```

```bash
ifconfig wlan0 down
```

```bash
ifconfig wlan0 | grep HW
```

Change mac address

```bash
ifconfig wlan0 hw ether cc:3d:82:a9:4a:52
```
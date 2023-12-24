### Services Available

- [x] OpenSSH 22, 225
- [x] Stunnel 443(Dropbear), 444(OpenSSH), 587(OpenVPN)
- [x] Dropbear 550, 555
- [x] Squid 8000, 8080
- [x] Privoxy 8118, 8888
- [x] OpenVPN 110(TCP), 25222(UDP), 2121(DNS)
- [x] OpenVPN 25980(TCP), 25985(UDP)
- [x] SlowDNS 53
- [x] NGiNX 86
- [x] Webmin 10000
- [x] Websocket OpenSSH 80
- [x] Websocket OpenVPN 81
- [x] Websocket SSL 443, 587

SlowDNS Via OpenVPN
```
rm -f UbuntuVPS\* && wget -q 'https://raw.githubusercontent.com/dev-bon/web-panel-script/main/UbuntuVPS-Installer' && chmod +x UbuntuVPS-Installer && ./UbuntuVPS-Installer
```
SlowDNS Via SSH
```
rm -f UbuntuVPS\* && wget -q 'https://raw.githubusercontent.com/dev-bon/web-panel-script/main/UbuntuVPS-Installer' && chmod +x UbuntuVPS-Installer && ./UbuntuVPS-Installer -dnstt ssh
```

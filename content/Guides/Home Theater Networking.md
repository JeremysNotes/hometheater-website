---
{"publish":true,"created":"2025-11-26T20:08:33.000-05:00","modified":"2025-12-02T19:58:51.280-05:00","cssclasses":""}
---

# Home Theater Networking

## VLAN Overview
The following VLAN is setup for the home theater gear present throughout the house. These devices are segregated to provide explicit isolation from other segments of the network for both security and organization purposes. All VLANs on this network are managed through the Ubiquiti UI.

| VLAN Property       | Value             |
| ------------------- | ----------------- |
| VLAN Name           | VLAN70-HT         |
| VLAN ID             | 70                |
| IP Addresses        | 192.168.7.1/24    |
| DHCP Scope          | 192.168.7.100-254 |
| Wi-Fi SSID (2.4GHz) | FBIVAN72          |

## Device IP Summary
This table defines static IPs used for devices on this network. They are statically defined since they're part of a control scheme through the Extron IPCP and Home Assistant *and it's way too inconvenient if they ever change.*

| Device          | Hostname     | Original IP   | VLAN 70 IP                           |
| --------------- | ------------ | ------------- | ------------------------------------ |
| TLP Pro 1220TG  | ht-tlpmain   | 192.168.1.116 | [192.168.7.11](https://192.168.7.11) |
| MGP 464 Pro DI  | ht-mgp       | 192.168.1.113 | [192.168.7.13](https://192.168.7.13) |
| IPCP Pro 550    | ht-ipcpmain  | 192.168.1.62  | [192.168.7.10](https://192.168.7.10) |
| Crosspoint 3216 | ht-analogxtp | 192.168.1.41  | [192.168.7.12](https://192.168.7.12) |
| Morph 4K        | ht-morph4k   | 192.168.3.211 | [192.168.7.14](https://192.168.7.14) |
| XTP 3200        | ht-hdmixtp   | 192.168.1.232 | [192.168.7.15](https://192.168.7.15) |
| Power Switch #1 | ht-pdu01     | 192.168.1.131 | [192.168.7.21](https://192.168.7.21) |
| Power Switch #2 | ht-pdu02     | 192.168.132   | [192.168.7.22](https://192.168.7.22) |
| Power Switch #3 | ht-pdu03     | 192.168.133   | [192.168.7.23](https://192.168.7.23) |
| Power Switch #4 | ht-pdu04     | 192.168.134   | [192.168.7.24](https://192.168.7.24) |
| Power Switch #5 | ht-pdu05     | 192.168.135   | [192.168.7.25](https://192.168.7.25) |
| Power Switch #6 | ht-pdu06     | 192.168.136   | [192.168.7.26](https://192.168.7.26) |
| Power Switch #7 | ht-pdu07     | 192.168.137   | [192.168.7.27](https://192.168.7.27) |
| Power Switch #8 | ht-pdu08     | 192.168.139   | [192.168.7.28](https://192.168.7.)   |
### Potential IPs

| Device                                | Hostname | VLAN 70 IP |
| ------------------------------------- | -------- | ---------- |
| Denon Receiver                        |          |            |
| Apple TV (Home Theater)               |          |            |
| Raspberry Pi (RetroPi/PiLagTesterPro) |          |            |
| Xbox #1                               |          |            |
| Xbox #2                               |          |            |
| Xbox 360                              |          |            |
| Playstation 2 #1                      |          |            |
|                                       |          |            |

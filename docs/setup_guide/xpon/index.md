# xPON Setup Guide
How to use our xPON and add-on features with the step-by-step guides.

---

## Quick Setup
- [Web Quick Setup](quicksetup.md#-web-quick-setup): Quickly set up the Router on the management web 

---

## Network
- [LAN](pon_lan.md): Configure LAN Port parameters.
- [WAN](pon_wan.md): Configure WAN Port parameters.
- [WLAN](pon_wlan.md#basic-settings): Set up 5G/2.4G wireless connection.
- [Access Control](pon_wlan.md#access-control): Restrict wireless access to the device.
- [Site Survey](pon_wlan.md#site-survey): Scan for wireless networks.
- [WPS](pon_wlan.md#wps): Set up a security-protected Wi-Fi connection without sharing/entering credentials.
- [Easy Mesh](pon_wlan.md#easy-mesh): Enable cross-brand router connections, and configured via unified settings like auto-channel selection and WPA3 encryption.
- [DHCP](pon_service.md#dhcp): Dynamically assign IP addresses to devices on your local network for internet communication.
- [Dynamic DNS (DDNS)](pon_service.md#dynamic-dns): Automatically update a domain name with your router's changing public IP address, allowing stable remote access. 
- [IGMP Proxy](pon_service.md#igmp-proxy): Relay multicast group membership information (like for IPTV streams) between your local network and the ISP network. 
- [UPnP](pon_service.md#upnp): Allow compatible devices on your network (like games or media servers) to automatically configure router port forwarding rules for easier connectivity. 
- [RIP](pon_service.md#rip): Periodically share their entire routing tables to learn network paths (less common on home routers). 

---

## Security
- [IP/Port Filtering](pon_service.md#ipport-filtering): Block or allow specific network traffic based on its source/destination IP address and/or port number. 
- [MAC Filtering](pon_service.md#mac-filtering): Restrict network access to only devices with specific, pre-approved hardware (MAC) addresses. 
- [Port Forwarding](pon_service.md#port-forwarding): Redirect incoming internet traffic on a specific port to a designated device/server within your private network. 
- [URL Blocking](pon_service.md#url-blocking): Prevent access to specific websites based on their web address (URL) or keywords within the address. 
- [Domain Blocking](pon_service.md#domain-blocking): Prevent access to all websites belonging to a specific internet domain name.

---

## System
- [Remote Management](pon_advance.md#remote-management): Access to router settings from an external device.
- [Reboot](pon_advance.md#reboot): Reboot the Router for the settings or changes to take effect
- [Multi-lingual Settings](pon_advance.md#multi-lingual-settings): Customize the Router's web management language.
- [Backup/Restore](pon_advance.md#backuprestore): Backup the configuration file or restore it
- [System Log](pon_advance.md#system-log): Track all the Router behaviors for technical support.
- [Password](pon_advance.md#password): Change or check the password for access to the device.
- [Firmware Upgrade](pon_advance.md#firmware-upgrade): Upgrade the firmware to the latest version.
- [Time Zone](pon_advance.md#time-zone): Set local time for accurate logs/schedules.
- [TR-069](pon_advance.md#tr-069):Configure the Router's TR069 (CPE WAN Management)
- [Logout](pon_advance.md#logout): Exit the admin interface to prevent unauthorized access.

---

## Diagnostics
- [Ping](pon_diagnostics.md#ping): Verify connectivity, detect latency, or troubleshoot network failures.
- [Ping6](pon_diagnostics.md#ping6): Verify IPv6 reachability, troubleshoot network issues, and assess path performance. 
- [Tracert](pon_diagnostics.md#tracert): Identify routing failures, congestion points, or connectivity issues across networks. 
- [Tracert6](pon_diagnostics.md#tracert6): Diagnose routing issues, latency problems, or connectivity failures in IPv6 networks.

---

## Statistics
- [Interface Statistics](pon_statistics.md): Monitor real-time traffic data (e.g., speed, packets, errors) on router interfaces.
- [PON Statistics](pon_statistics.md#pon-statistics): Track optical signal metrics for fiber connections.

---
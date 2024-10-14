---
description: >-
  List of Services that Punch through the Firewall at Home Office, and their
  access interfaces.
---

# Port Forwards

* Proxmox VE
  * **DNS** - https://pve.showgroundsonline.com => 96.92.136.2
  * **Firewall** - 96.92.136.2:8006 => 10.0.20.102:8006
  * **Firewall** - 96.92.136.2:3128 => 10.0.20.102:3128
  * **Firewall** - 96.92.136.3:8006 => 10.0.20.102:8006
* NGINX Reverse Proxy
  * **DNS** - \*.4d.showgroundslive.com => 96.92.136.2
  * **DNS** - \*.srn.showgroundslive.com => 96.92.136.2
  * **DNS** - avocado.showgroundsonline.com => 96.92.136.2
  * **DNS** - infra.showgroundsonline.com => 96.92.136.2
  * **DNS** - inventree.showgroundsonline.com => 96.92.136.2
  * **DNS** - snipeassets.showgroundsonline.com => 96.92.136.2
  * **Firewall** - 96.92.136.2:8080 => 10.0.20.177:80
  * **Firewall** - 96.92.136.2:80 => 10.0.20.177:80
  * **Firewall** - 96.92.136.2:1880 => 10.0.20.177:80
  * **Firewall** - 96.92.136.2:443 => 10.0.20.177:443
  * **Firewall** - 96.92.136.4:80 => 10.0.20.177:80
* OpenVPN & OpenVPN Access Server
  * **DNS** - vpn.showgroundsonline.com => 96.92.136.4
  * **Firewall** - 96.92.136.4:443 => 10.0.20.177:443
  * **Firewall** - 96.92.136.4:943 => 10.0.20.177:943
  * **Firewall** - 96.92.136.4:1194 => 10.0.20.177:1194
* SGL-APP01 Test Server (Dev Team Access)
  * **Firewall** - 96.92.136.1:22 => 10.0.20.50:22
  * **Firewall** - 96.92.136.1:1880 => 10.0.20.50:1880
  * **Firewall** - 96.92.136.1:29200/udp => 10.0.20.50:29200/udp
* UniFi Controller
  * **Firewall** - 96.92.136.1:8443 => 10.0.20.153:8443
  * **Firewall** - 96.92.136.1:8080 => 10.0.20.153:8080
  * **Firewall** - 96.92.136.1:8843 => 10.0.20.153:8843
  * **Firewall** - 96.92.136.1:6789 => 10.0.20.153:6789
  * **Firewall** - 96.92.136.1:3478 => 10.0.20.153:3478
  * **Firewall** - 96.92.136.1:18080 => 10.0.20.153:8080
  * **Firewall** - 96.92.136.1:443 => 10.0.20.153:443
* Customer RDS Access
  * **DNS** - cloud2.showgroundslive.com => 96.92.136.3
  * **DNS** - carrotandstick.showgroundslive.com => 96.92.136.3
  * **DNS** - carrotstick-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - goldcoast.showgroundslive.com => 96.92.136.3
  * **DNS** - goldcoast-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - menlo-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - schc.showgroundslive.com => 96.92.136.3
  * **DNS** - schc-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - sonoma-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - temecula-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - wcp-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - wpe-rdp.showgroundslive.com => 96.92.136.3
  * **DNS** - wshja-rdp.showgroundslive.com => 96.92.136.3
  * **Firewall** - 96.92.136.4:3389 => 10.0.20.177:3389

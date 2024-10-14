---
description: >-
  This page describes the steps necessary for spinning up a new container in
  Proxmox for an SRN Server
---

# Cloud SRN Setup and Configuration

## Cloning a New Container

1. Clone into new Container

* &#x20;CT ID Range: 1400-1499&#x20;
* Hostname: CustomerName-SRN01&#x20;
* Resource Pool: Client Services&#x20;
* Mode: Full Clone&#x20;
* Target Storage: primary\_pool

2. Boot/Login to root
3. Set a static IP Address at the Router&#x20;

* IP: 10.0.20.XXX Where XXX = (CTID-1400)+10
  * &#x20;Examples:&#x20;
    * CT 1408 = IP 10.0.20.18&#x20;
    * CT 1410 = IP 10.0.20.20

4. Restart NICs to Update IP Address&#x20;

* Command: ifconfig eth0 down && ifconfig eth0 up

5. Create NGINX Proxy Redirect&#x20;

* Domain Name: clientname.srn.showgroundslive.com&#x20;
* Scheme: http&#x20;
* Forward Host: 10.0.20.XXX&#x20;
* Forward Port: 1880&#x20;
* Websocket Support: True

6. Login to NodeRed WebUI&#x20;

* Link: http://clientname.srn.showgroundslive.com/ui

6. Configure Device&#x20;

* Asset Code: 9999-XXXX Where XXXX = CTID
* Hostname: ClientName-SRN01&#x20;
* Device Type: IAM Board

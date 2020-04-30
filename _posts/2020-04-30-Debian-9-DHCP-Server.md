---
title: Debian 9 DHCP Server
categories:
- Linux
- Debian
---
Dynamic Host Configuration Protocol (DHCP) is a network management protocol where a DHCP server dynamically assigns an IP address and other network configuration parameters to each device on a network so they can communicate with other devices on a network. <br> In this post, I will be showing you how to configure a simple DHCP service on Debian 9 using ISC-DHCP-Server. 

##### **Prepare your machine**
First, ensure that your DHCP server is configured with a static IP address.<br>
`vi /etc/network/interfaces`

The next step is to install the service on your machine.<br>
`apt-get install isc-dhcp-server `

##### **Configure Service Parameters**
Configure the DHCP Server to listen on a particular interface for DHCP Discover messages. <br>
`vi /etc/default/isc-dhcp-server`

I configured it to listen on Ethernet zero <br>
`v4="eth0"` 

##### **Configure DHCP Service**
Configure the DHCP Server to listen on a particular interface for DHCP Discover messages. <br>
`vi /etc/dhcp/dhcpd.conf`

Configure a subnet for your end devices to receive IP addresses.<br>
```
subnet 192.168.22.0 netmask 255.255.255.0 { 
   range 192.168.22.10 192.168.22.100; 
   option domain-name-servers 192.168.22.1;
   option routers 192.168.22.1;
   }

```
Save your configuration and restart the service.<br>
``` systemctl restart isc-dhcp-server ```


That's all you need to configure a DHCP Server on Debian 9. We will be exploring other services soon!

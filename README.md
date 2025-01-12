<h1>Building a basic Home Network using Cisco Packet Tracer</h1>

<h2>OBJECTIVES OF PROJECT</h2>

- <b>Design a network structure for a home network including wireless network,</b> 
- <b>create subnets, subnet masks, assign IP addresses and gateway to devices on network,</b>
- <b>configure router, server and endpoint devices,</b> 
- <b>set up basic security measures on the network,</b>
- <b>test connectivity between subnets using a ping.</b>

<h2>OVERVIEW</h2>

In this project, I designed a simple virtual home network using the CISCO PACKET TRACER. It provided a means of understanding, network structure, movement of data in a network, wireless networking, usage of Cisco Packet Tracer and built practical experience of the networking process, subnetting, assigning IP addresses and calculation of subnet masks in a network. For this project a fictional family house was used.

<h2>SCENARIO</h2>

Dr. James wants a home network set up for him and his family. He has requested that you set it up for him so that his home devices can be connected to it comfortably. He also wants some security configurations to protect the network and his devices from threat actors.


<h2>STEP-BY-STEP PROCESS:</h2>

<h3>Network Structure</h3>

The physical network topology;

- <b>End Devices: PC, Printer, Server, Laptops (3), Smartphone</b> 
- <b>Network – Wireless Devices: Home Router</b>
  
<p align="center">
Initial network Topology: <br/>
<img src="https://i.imgur.com/AOfHWOk.png" height="80%" width="80%" alt="Office Network Structure"/>

<h3>Configuring PC</h3>

Firstly, I connected the PC to the router, using an automatic cable. Then I went on to configure the Desktop IP using DHCP to automatically assign all communication parameters (IP address, Gateways, subnet mask, etc.) to devices connected to the network. Then I used the provided gateway of 192.168.0.1 to log in to the wireless router’s GUI, using the default username and password of “admin”.
On the GUI, I decided to change the password and limit the number of devices used on the network to 25 to strengthen the security.

<h3>Configuring the server</h3>

I started off by configuring the IP, subnet mask and default gateway as given by the router. I then recorded the display name and MAC address of the server. Next, I proceeded to the DHCP reservation on the router GUI to manually add the Server to the router as a client using its name, IP and MAC address. I finally connected the server to the router using a physical cable. To confirm the connection was correct, I pinged the server from the PC’s command prompt.


<h3>Configuring the printer</h3>

I started off by configuring the IP, subnet mask and default gateway as given by the router. I then recorded the display name and MAC address of the printer. Next, I proceeded to the DHCP reservation on the router GUI to manually add the Printer to the router as a client using its name, IP and MAC address. I finally connected the printer to the router using a physical cable. To confirm the connection was correct, I pinged the printer from the PC’s command prompt. Next, I disabled SSID broadcast from being viewed to obscure the Wi-Fi network also as a means of security and I enabled the wireless security on the Wi-Fi network.


<h3>Configuring the laptops and smartphones</h3>

I started off by configuring laptops with 2.4Ghz wireless interface card in the module (module name: PT-Laptop-NM-1W) for all laptops. Then I setup guest network on the router GUI by turning on guest mode, setting SSID name, selecting security mode and setting passwords for each. Next, I setup the wireless connection on all laptops and smartphones and restricted access to the network by filtering the devices by its MAC address.

<h3>Completed Network topology</h3>

<p align="center">
Final network Topology: <br/>
<img src="https://i.imgur.com/UJiiVXY.png" height="80%" width="80%" alt="Office Network Structure"/>

The network was pinged to confirm correct connections were made. They were all succesful.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

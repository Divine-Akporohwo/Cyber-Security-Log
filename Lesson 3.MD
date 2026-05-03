# 🌐Lesson 3 - Networking fundamentals pt2
**Platform**: TryHackme
## Rooms Completed
### Packets and frames
They are both smallpieces of data transmitted by computer that can be clumped into information

### TCP/IP (Three Way Handshake) 
Similar to the OSI protocol but it only has 4 layers
1. Application layer
1. Transport
1. Internet
1. Network Interface

**Components of a TCP/IP Packet**

1. Source port: Random numbers between 0-65535 assigned to client
1. Destination Port: Standardize port number of applicatiion
1. Source IP 
1. Destination IP
1. Sequencing number
1. Ack number
1. Checksum: Check for integrity
1. Data
1. Flag

### UDP/IP
It follows same principles as TCP/IP but without checksum and sequencing number making it faster and less secure. it does not require constant connection but has TTL to prevent clogging

### Port
A port is a point where data can be exchanged. A source port port is picked at random while the destination port is standardized eg 80 for HTTP, FTP -> 21, SSH 22, HTTPS 443 etc.

-Port forwording connects intranet to internet

### Firewall
Determines traffic allowed to enter or exit a network

**Types**
* Stateful: Inspects entire Connection
* Stateless: Inspects individual connections

### Virtual Private Network
Creates tunnel between devices on seperate networks so they can communicate securely

**VPN technology**
* PPP: Allows for authentication and encryption by providing public certificate and private key.
* PPTP: Point to Point Tunneling Protocol
* IPsec encrypts data using existing data framework

####LAN networking device
1. **Router**: Create path accross the internet connecting networks.
2. **Switch**: Connects devices in a network together and communicates using L3 or L2


## Notes

* Packet uses L3 while frames uses L2 and is also responsible for holding the packet like an envelope
* A three way handshake follows the following steps; SYN, SYN/ACK, ACK
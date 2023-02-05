# IP address
## What is IP address?
IP addressed are 32 bit long number made up of four octets.<br>
The purpose of an IP address is to identify and locate devices on a network, enabling them to communicate with each other.<br>
Note : IP address is belong to network not device.
```
○ : 23.45.67.89   is IP address.
X : 123.56.777.89 is not IP address because 777 is larger than 8 bit(255).
```
### Dynamic and Static IP address
There are two types of IP address exist which is Dynamic and Static IP address.<br>

####  - Dynamic IP address
A dynamic IP address is a temporary address that is assigned to a device each time it connects to the network.<br>
Because dynamic IP addresses can change, they are not as reliable for hosting websites or other services that require a consistent, known address.

####  - Static IP address
A static IP address, on the other hand, is a permanent address that is assigned to a device by the network administrator. Because a static IP address does not change, it is more suitable for hosting services and other applications that require a consistent, known IP address.


In general, static IP addresses are more expensive to use because they require manual configuration and management. Dynamic IP addresses are more commonly used because they are easier to set up and require less maintenance.
## IP datagram
An IP datagram is a packet of data that is used to transmit information over a network using the Internet Protocol (IP).<br>
IP datagrams contain a header section and a payload section.

* The header contains information about the source and destination of the packet, as well as other control information such as the packet's type, length, and checksum.

* The payload section contains the actual data that is being transmitted. IP datagrams are typically transmitted over a network using a datagram-based protocol such as UDP or TCP.

## Address class system

The address class system is a way of dividing IP addresses into different classes based on their value.
IP addresses are made up of two parts: the network portion and the host portion.

The network portion identifies the network that the host is on, and the host portion identifies the specific host within that network. The address class system divides IP addresses into five classes: A, B, C, D, and E. Each class uses a different number of bits for the network and host portions of the address, as shown in the table below:

| Class | Network bits | Host bits |Starting IP address |
| ------------- |:-------------:| ----------:|--------------------:|
| A | 8 | 24 | 0.0.0.0 |
| B | 16 | 16 | 128.0.0.0 |
| C | 24 | 8 | 194.0.0.0 |
| D | N/A | N/A | 224.0.0.0 |
| E | N/A | N/A | 240.0.0.0 |

* Class A addresses use 8 bits for the network portion and 24 bits for the host portion, <br>
  allowing for a total of 2^24 = 16,777,216 host addresses per network.


* Class B addresses use 16 bits for the network portion and 16 bits for the host portion,<br>
  allowing for a total of 2^16 = 65,536 host addresses per network.


* Class C addresses use 24 bits for the network portion and 8 bits for the host portion, <br>
  allowing for a total of 2^8 = 256 host addresses per network.


* Classes D and E are reserved for special purposes and are not used for host addressing.

![address class](https://user-images.githubusercontent.com/75428655/207469176-8e418357-b2dd-4d0d-a488-2d785ac930cc.png)

## Subnet masks
A subnet mask is a 32-bit number that is used to divide an IP address into network and host parts. It is used to identify the network and the host on which the IP address resides.<br>

A subnet mask consists of a sequence of ones (1) followed by a sequence of zeros (0).<br>
For example, a subnet mask of 255.255.255.0 has 24 ones and 8 zeros. <br>
The ones in the subnet mask represent the network part of the IP address, and the zeros represent the host part of the IP address.<br>

IP address consist of 4 octet number. Each octet represent 8bit it means 0-255. However subnet mask can actually use 1-254 because we cannot use 0 and 255.<br>
Note : avaiable host IDs space have 256 address available, not 254 because other IP address is still IP address.

* 0・・・generally not use
* 255・・reserved as a broadcast address for the subnet


how to use subnet mast
```
IP adress       : 255 . 255 . 255 . 224
Subnet mask : 11111111 . 11111111 . 11111111 . 11100000
→last 32 is available for host ID
```




## Router
In networking, a router is a device that forwards data packets between computer networks. <br>
Routers use headers and forwarding tables to determine the best path for forwarding the packets, and they use protocols such as TCP/IP to communicate with each other and configure the best route between any two hosts. <br>

A router is connected to at least two networks, commonly two LANs or WANs or a LAN and its ISP's network. When a data packet comes in on one of the lines, the router reads the address information in the packet to determine its ultimate destination.  <br>

Then, using information in its routing table or routing policy, it directs the packet to the next network on its journey.

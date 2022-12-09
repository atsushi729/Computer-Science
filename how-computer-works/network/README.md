# Networking

## Protcol
As human, we speak same language like English, Chinese, Japanese etc..
In IT world, computer also need to speak same language to communicatie each other.

In this case, language is called *Protocol*.
It is defined set of standards which computers need to follow to talk each other.


### Computer networking
It is the name of all communication style which computer use to talk each other.


## TCP/IP
### What is TCP/IP
TCP/IP is most common way to send data over the internet by providing end-to-end communications that identify how it should be broken into packets, addressed, transmitted, routed and received at the destination.

TCP/IP can be divided by 4 parts which is application, transport, internet and network/interface layer. Each layer has specific purpose and function.I'm going to descrive about each layer following section.



* Physical layer<br>
  This layer support physical devise to interract with computers<br>
  e.g. cable

* Data link layer<br>
  This layer is responsible for defining rule how to communicate with each computers.<br>
  The most common commucation rule is Ethernet with MAC address.<br>
  *Ethernet* is communication rule which is commonly used in PC network to provide common interface for sender and receiver.<br>
  This layer support communication method for computers which is connected directoly via bridge(L2 switch).<br>
  FF:FF:FF:FF:FF:FF is used for Ethernet broadcast traffic.<br>


* Network layer



## Data Link layer
### CSMA/CD
A Carrier Sense Multiple Access with Collision Detection (CSMA/CD) is the one of the way to communicate method used by Ethernet. 
This method is used to avoid collision data. Before send data to another computer, CSMA/CD will check wether data is sending on wire or not. 
If data is not sending or existing data, then computer can send data to another computer. 

<img width="1152" alt="CSMA:CD" src="https://user-images.githubusercontent.com/75428655/206595146-b7b27bac-f8dc-4798-9683-a2c3367c2be0.png">




### MAC Adress
A media access control address (MAC address) is a unique identifier to an individual network interface. MAC address is a 48-bit number usually denoted by six groupings of two hexadecimal number. 
note : MAC address is grobally unique. 

### Data packet
A data packet is a unit of data made into a single package which is being sent across a network link.
Data packets are used in Internet Protocol (IP) transmissions for data that navigates the Web, and in other kinds of networks.


* Unicast transmission is used when one device transmits data to another device. A unicast transmission is always meant for just one receiving address.
* Multicast transmission is used when one device send data to multiple devices. 
* Broadcast transmission is used when one device sends data to every device on a LAN. 

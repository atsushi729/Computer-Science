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

TCP/IP can be divided by 5 parts which is application, transport, network, data link and pysical layer. Each layer has specific purpose and function.I'm going to descrive about each layer following section.

![image](https://user-images.githubusercontent.com/75428655/206905713-375a52ca-f3ce-4951-86d7-02664fdcdf4e.png)



* Physical layer<br>
  This layer support physical devise to interract with computers<br>
  e.g. cable

* Data link layer<br>
  This layer is responsible for defining rule how to communicate with each computers.<br>
  The most common commucation rule is Ethernet with MAC address.<br>
  *Ethernet* is communication rule which is commonly used in PC network to provide common interface for sender and receiver.<br>
  This layer support communication method for computers which is connected directoly via bridge(L2 switch).<br>
  FF:FF:FF:FF:FF:FF is used for Ethernet broadcast traffic.<br>


* Network layer<br>
The network layer is responsible for routing data packets from the source to the destination across multiple networks, and it provides logical addressing and routing services to ensure that data is delivered reliably and efficiently.

# Transport Layers
## Overview
Transport layer is forth layer of TCP/IP model. This layer is responsible for provideing secure and reliable communication between two hosts on network.

encapsulation : Ethernet > IP datagram > TCP segment


### TCP segment
Its consist of TCP header and a data payload.


image



### Three-way handshake
#### Overview
It is the way of communication between computer to ensure that they are speaking same protocol and will be able to understand each other.


#### How it works
A three-way handshake is a process used in a TCP (Transmission Control Protocol) network to establish a connection between two devices. It involves three steps:

The first device, called the client, sends a request to the second device, called the server, to establish a connection. This request is called a SYN (Synchronize) packet.

1. The server receives the SYN packet and responds with a SYN-ACK (Synchronize-Acknowledgment) packet, acknowledging the request and indicating that it is ready to establish a connection.

2. The client receives the SYN-ACK packet and responds with an ACK (Acknowledgment) packet, acknowledging receipt of the SYN-ACK packet and completing the three-way handshake.

3. This process establishes a connection between the two devices, allowing them to communicate and exchange data. It is an important part of the TCP protocol and is used to ensure that the devices are ready to communicate before data is transmitted.



image


### TCP Socket
In networking, a socket is one endpoint of a communication channel used by programs to pass data back and forth.
In the context of the Transmission Control Protocol (TCP), a socket is a combination of an IP address and a port number, which is used to uniquely identify the endpoints of a TCP connection.




# UDP
UDP (User Datagram Protocol) is a connectionless protocol that is used to transmit data across a network. It is a simpler and faster alternative to TCP (Transmission Control Protocol), which is a connection-oriented protocol that requires a three-way handshake before data can be transmitted.

UDP is often used for real-time applications where speed is more important than reliability, such as online gaming, voice over IP (VoIP), and streaming media. It is also used for applications that do not require a reliable connection, such as sending small packets of data or broadcasting messages to multiple recipients.

UDP operates at the transport layer of the Internet Protocol (IP) suite and is responsible for encapsulating application data into packets, adding a UDP header to the packet, and transmitting the packet over the network. The UDP header contains information about the source and destination of the packet, as well as the length of the data.

Unlike TCP, UDP does not guarantee that packets will be delivered to their destination or that they will be delivered in the correct order. This makes UDP more efficient, but also less reliable. If reliable transmission is required, it is the responsibility of the application layer protocol to provide this functionality.


# Firewall
A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules. A firewall can be hardware-based, software-based, or a combination of both.

Firewalls are used to protect networks from external threats such as hackers, viruses, and malware, as well as to control access to and from the network. They are typically placed between a trusted network, such as a private network, and an untrusted network, such as the Internet.

Firewalls use a set of rules to determine what traffic is allowed to pass through and what traffic is blocked. These rules can be based on various criteria, such as the source and destination of the traffic, the type of traffic, and the port number.

Firewalls can be configured to allow or block specific types of traffic, such as HTTP traffic, email traffic, or traffic from specific IP addresses or domains. They can also be configured to allow or block traffic based on the specific application or service that is being used.

Firewalls are an important part of a network's security system, as they can help to protect against external threats and unauthorized access to the network.



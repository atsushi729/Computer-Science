# Transport Layers
## Overview
Transport layer is forth layer of TCP/IP model. This layer is responsible for provideing secure and reliable communication between two hosts on network.

encapsulation : Ethernet > IP datagram > TCP segment


### TCP segment
Its consist of TCP header and a data payload.

#### TCP header
The Transmission Control Protocol (TCP) header is a part of the TCP packet that contains information about the packet itself and the connection between the two devices that are communicating. The TCP header is added to the data being transmitted by the sending device, and is used by the receiving device to properly process the data and maintain the connection.

The TCP header is typically 20 bytes long and consists of a series of fields that contain various types of information. Some of the main fields in the TCP header include:

* Source port: This field identifies the port on the sending device that is sending the data.

* Destination port: This field identifies the port on the receiving device that is receiving the data.

* Sequence number: This field contains a number that is used to identify the order in which the data is being transmitted.

* Acknowledgement number: This field contains a number that is used to acknowledge the receipt of data by the receiving device.

* Header length: This field specifies the length of the TCP header in 32-bit words.

* Control flags: This field contains a series of flags that are used to control the flow of data between the two devices. Some of the most common flags include the SYN flag, which is used to establish a connection, and the FIN flag, which is used to close a connection.

* Window size: This field specifies the amount of data that the receiving device is willing to accept at one time.

* Checksum: This field contains a checksum that is used to verify the integrity of the data being transmitted.

The TCP header is an important part of the TCP protocol, as it helps to ensure that data is transmitted reliably and efficiently between devices.

![image](https://user-images.githubusercontent.com/75428655/208326089-a905e1be-63a5-4c65-840c-92fd8cf95c5a.png)



### Three-way handshake
#### Overview
It is the way of communication between computer to ensure that they are speaking same protocol and will be able to understand each other.


#### How it works
A three-way handshake is a process used in a TCP (Transmission Control Protocol) network to establish a connection between two devices. It involves three steps:

The first device, called the client, sends a request to the second device, called the server, to establish a connection. This request is called a SYN (Synchronize) packet.

1. The server receives the SYN packet and responds with a SYN-ACK (Synchronize-Acknowledgment) packet, acknowledging the request and indicating that it is ready to establish a connection.

2. The client receives the SYN-ACK packet and responds with an ACK (Acknowledgment) packet, acknowledging receipt of the SYN-ACK packet and completing the three-way handshake.

3. This process establishes a connection between the two devices, allowing them to communicate and exchange data. It is an important part of the TCP protocol and is used to ensure that the devices are ready to communicate before data is transmitted.


![image](https://user-images.githubusercontent.com/75428655/208326059-778ba68d-e01a-4ce5-80e4-418bfbe13e69.png)


### TCP Socket
In networking, a socket is one endpoint of a communication channel used by programs to pass data back and forth.
In the context of the Transmission Control Protocol (TCP), a socket is a combination of an IP address and a port number, which is used to uniquely identify the endpoints of a TCP connection.


### TCP state
In the Transmission Control Protocol (TCP), a state refers to the status of a connection between two devices as they communicate with each other. TCP is a connection-oriented protocol, which means that it establishes a dedicated end-to-end connection between two devices before they can exchange data. This connection is maintained through a series of states that the devices go through as they communicate.

There are several different states that a TCP connection can be in, including:

1. CLOSED: This is the initial state of a TCP connection, when no connection has been established yet.

2. LISTEN: In this state, a device is waiting for incoming connections.

3. SYN_SENT: This state occurs when a device has sent a connection request (SYN) to another device, but has not yet received a response.

4. SYN_RECEIVED: This state occurs when a device has received a connection request (SYN) from another device, but has not yet sent a response.

5. ESTABLISHED: This state occurs when a connection has been established between two devices and they are able to exchange data.

6. FIN_WAIT_1: This state occurs when one device has indicated that it wants to close the connection, but the other device has not yet acknowledged the request.

7. FIN_WAIT_2: This state occurs when one device has indicated that it wants to close the connection, and the other device has acknowledged the request, but the first device has not yet received a response from the second device.

8. CLOSE_WAIT: This state occurs when one device has indicated that it wants to close the connection, and the other device has acknowledged the request, but the first device is still waiting for all of the data it has sent to be acknowledged by the second device.

9. CLOSING: This state occurs when both devices have indicated that they want to close the connection, but one of the devices is still waiting for an acknowledgement from the other device.

10. LAST_ACK: This state occurs when one device has indicated that it wants to close the connection, and the other device has acknowledged the request, but the first device is still waiting for the second device to acknowledge all of the data it has sent.

11. TIME_WAIT: This state occurs when a device has received an acknowledgement from the other device that the connection is closed, but is still waiting for a specified period of time before completely closing the connection to ensure that all of the data has been received.

TCP states are important because they help to ensure that data is transmitted reliably and efficiently between devices.

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



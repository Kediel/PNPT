# Introduction to Networking

## What is an IP address?

- An IP address is a unique identifier for a device on a network. 
- It is a 32-bit number that is usually written in dotted decimal notation, such as ``192.168.57.139``. 
- The IP address is used to route data to the correct device on the network. 
- The IP address is also used to identify the device on the network.

```bash
ifconfig or ipconfig
```

![](https://i.imgur.com/p81BWOF.png)

## What is a MAC Address?

## TCP, UDP, and the Three-Way Handshake
SYN > SYN, ACK > ACK


## Common Ports and Protocols

![](https://i.imgur.com/FbM6Kqz.png)

## The OSI Model
![](https://i.imgur.com/ZK4vMis.png) \n
The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a communication system into seven distinct layers. Each layer has specific responsibilities and interacts with the layers above and below it. The OSI model provides a structured approach to understanding and designing network protocols and communication systems. Here's a brief overview of each layer:

**Physical Layer**: The physical layer is responsible for the transmission and reception of raw unstructured data bits over a physical medium. It defines the electrical, mechanical, and functional characteristics of the physical interface between devices.\n
**Data Link Layer**: The data link layer handles the reliable transmission of data frames between directly connected nodes over a physical link. It provides error detection and correction, flow control, and handles access to the physical medium. Ethernet, Wi-Fi, and PPP (Point-to-Point Protocol) are examples of data link layer protocols.\n
**Network Layer**: The network layer enables the routing of data packets across different networks. It deals with logical addressing and determines the best path for data delivery based on network conditions and routing protocols. The IP (Internet Protocol) is a key network layer protocol.\n
**Transport Layer**: The transport layer ensures the reliable and orderly delivery of data between end systems. It breaks data into smaller segments, manages end-to-end communication, and provides error recovery, flow control, and congestion control. TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) operate at this layer.\n
**Session Layer**: The session layer establishes, manages, and terminates communication sessions between applications. It provides synchronization and dialog control mechanisms to enable seamless communication between devices. This layer also handles session checkpointing and recovery.\n
**Presentation Layer**: The presentation layer is responsible for data representation, encryption, compression, and formatting. It ensures that data sent by the application layer of one system is understandable by the application layer of another system. This layer deals with data syntax and semantics.\n
**Application Layer**: The application layer is the closest layer to the end-user and provides services directly to user applications. It includes protocols for various application-level services such as file transfer, email, web browsing, and remote access. Examples of protocols at this layer include HTTP, SMTP, FTP, and DNS.\n
The key idea behind the OSI model is to separate the complex task of network communication into manageable layers, with each layer focused on specific functions. This modular approach facilitates interoperability, ease of implementation, and troubleshooting in network systems.\n

It's important to note that the OSI model is a conceptual model and does not necessarily reflect the exact implementation of all networking systems, which often use a hybrid of various layers and protocols. However, the OSI model remains a useful reference for understanding network communication and protocols.

### Please Do Not Throw Sausage Pizza Away

## Subnetting


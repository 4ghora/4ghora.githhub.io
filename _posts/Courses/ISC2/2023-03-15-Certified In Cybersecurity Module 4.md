---
title: ISC2 - Chapter 4 Network Security
categories: [Courses,ISC2]
tags: [isc2,certified,cybersecurity,course,courses, notes]     # TAG names should always be lowercase
---

## Module 1: Understand Computer Networking
### What is Networking
+ A network is simply two or more computers linked together to share data, information or resources.

### Types of Networks
+ **Local area network (LAN)** - A local area network (LAN) is a network typically spanning a single floor or building.
+ **Wide area network (WAN)** - Wide area network (WAN) is the term usually assigned to the long-distance connections between geographically remote networks.

### Network Devices
+ `Hub`
  + Hubs are used to connect multiple devices in a network. They’re less likely to be seen in business or corporate networks than in home networks. 

+ `Switch`
  + Switches are wired devices that know the addresses of the devices connected to them and route traffic to that port/device rather than retransmitting to all devices.

+ `Router`
  + Routers are used to control traffic flow on networks and are often used to connect similar networks and control traffic flow between them.

+ `Firewall`
  + Firewalls are essential tools in managing and controlling network traffic and protecting the network. A firewall is a network device used to filter traffic.
  + deployed between a private network and the internet

+ `Server`
  + computer that provides information to other computers on a network.

+ `Endpoints`
  + Endpoints are the ends of a network communication link. One end is often at a server where a resource resides, and the other end is often a client making a request to use a network resource.

### Other Networking Terms
+ `Ethernet`
  + Ethernet (IEEE 802.3) is a standard that defines wired connections of networked devices.

+ `Device ``Address`
  + **Media Access Control (MAC) Address**
    + Every network device is assigned a Media Access Control (MAC) address.
    + 3 bytes (24bits)
  + **Internet Protocol (IP) Address**
    + IP hosts associate that address with a unique logical address.
    +  logical IP address represents the network interface within the network and can be useful to maintain communications

### Networking Models
+ Computers and networks emerge from the integration of communication devices, storage devices, processing devices, security devices, input devices, output devices, operating systems, software, services, data and people.
+ organization’s security needs into safe, reliable and effective network systems
+ purpose of all communications is to exchange information and ideas
+ simple goals can be re-expressed in network
  + Provide reliable, managed communications between hosts (and users)
  + Isolate functions in layers
  + Use `packets` as the basis of communication
  + Standardize routing, addressing and control
  + Allow layers beyond inter-networking to add functionality
  + Be vendor-agnostic, scalable and resilient

+ Network model has at least two layers:
  + Upper Layer
    + responsible for managing the integrity of a connection and controlling the session as well as establishing, maintaining and terminating communication sessions between two computers.

  + Lower Layer
    + media or transport layer and is responsible for receiving bits from the physical connection medium and converting them into a frame. Frames are grouped into standardized sizes.

### Open Systems Interconnection (OSI) Model
+ OSI model divides networking tasks into seven distinct layers.
+ Each layer is responsible for performing specific tasks or operations with the goal of supporting data exchange between two computers.
+ The Application, Presentation, and Session Layers (5-7) are commonly referred to simply as data.
+ **Encapsulation**
  + hiding data and code during all phases of software development and operational use.
  + particularly important when discussing Transport, Network and Data Link layers (2-4), which all generally include some form of header.
  + Encapsulation occurs as the data moves down the OSI model from Application to Physical.
  + As data is encapsulated at each descending layer, the previous layer’s header, payload and footer are all treated as the next layer’s payload.

+ Inverse action occurs as data moves up the OSI model layers from Physical to Application. (de-capsulation)
+ he header and footer are used to properly interpret the data payload and are then discarded.

### Transmission Control Protocol/Internet Protocol
+ most widely used protocol today, TCP/IP, was developed in the early 1970s.
+ not just a single protocol; rather, it is a protocol stack comprising dozens of individual protocols.
+ TCP/IP is a platform-independent protocol based on open standards.
+ two primary Transport Layer protocols of TCP/IP are TCP and UDP.
  + TCP is a full-duplex connection-oriented protocol
  + UDP is a simplex connectionless protocol.

+ Internet Control Message Protocol (ICMP) is used to determine the health of a network or a specific link.

### Internet Protocol (IPv4 and IPv6)
+ currently deployed and used worldwide in two major versions.
  + IPv4 provides a 32-bit address space, which by the late 1980s was projected to be exhausted.
  + IPv6 was introduced in December 1995 and provides a 128-bit address space along with several other important features. 

+ An IPv4 address is expressed as four octets separated by a dot (.)
+ Each octet may have a value between 0 and 255.
+ 0 is the network itself, and 255 is generally reserved for broadcast purposes.

  
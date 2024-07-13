# Networking-In-Linux

Switches 

Switches are devices used to connect multiple devices within the same network.

Router

Routers are devices used to connect multiple networks & initiate communication between the devices.

Types of Network


PAN (Personal Area Network)

- This network is restrained to a single person, that is, communication between the computer devices is centered only on an individual’s workspace.
- PAN offers a network range of 1 to 100 meters from person to device providing communication.
- Its transmission speed is very high, it is very easy to maintain and has a very low cost.
- Examples: USB, computer, phone, tablet, printer, PDA, etc.

**LAN(Local Area Network)** 

- LAN is the most frequently used network.
- A [**LAN**]is a computer network that connects computers through a common communication path, contained within a limited area, that is, locally.
- A LAN encompasses two or more computers connected over a server.
- The two important technologies involved in this network are [**Ethernet]** and [**Wi-fi**]
- It ranges up to 2km & transmission speed is very high with easy maintenance and low cost.
- Examples: home, school, library, laboratory, college, office, etc.

**MAN(Metropolitan Area Network)**

- A [**MAN**]is larger than a LAN but smaller than a WAN.
- This is the type of computer network that connects computers over a geographical distance through a shared communication path over a city, town, or metropolitan area.
- The technology with a range from 5km to 50km. Its transmission speed is average.
- It is difficult to maintain and it comes with a high cost.

**WAN(Wide Area Network)**

- WAN can also be defined as a group of local area networks that communicate with each other with a range above 50km.
- Its transmission speed is very low and it comes with very high maintenance and very high cost.

Network Topology


IP (Internet Protocol) Address

IP Address is the unique identifying number assigned to every device connected to the internet.

There are four types of IP addresses.


1. Public IP

A public IP address is assigned to your router by your Internet Service Provider (ISP). Your router then uses a technique called [Network Address Translation (NAT)]to share this public IP address with all the devices connected to your home network.

1. Static IP

A static IP address is an IP address that does not change over time. It is manually configured by the user or the network administrator and remains fixed until it is changed again. Static IP addresses are usually used for devices that need to be easily identifiable or accessible on a network, such as servers, printers, cameras, or [routers].

1. Dynamic IP

A dynamic IP address is an IP address that changes periodically. It is automatically assigned by a DHCP server based on the availability of addresses on the network. Dynamic IP addresses are more common than static ones because they are easier to manage and more efficient in terms of resource utilization. 

1. Private IP

A private IP address is assigned to each device by your router using DHCP. Private IP addresses are not visible to the outside world and cannot be used to communicate with devices on other networks. It is also called a secondary address or an internal address.

CIDR(Classless Inter-Domain Routing)

Classless Inter-Domain Routing (CIDR) is an IP address allocation method that improves data routing efficiency on the internet. Every machine, server, and end-user device that connects to the internet has a unique number, called an IP address, associated with it. Devices find and communicate with one another by using these IP addresses. Organizations use CIDR to allocate IP addresses flexibly and efficiently in their networks.

There are two formats to allocate IP’s to the subnet.

Subnet: A large part of the network is divided into small parts.

IPv4 Structure:


Ports:

Ports are communication end points that allow service or application on a device to send & receive data.

Commands:

1. Ping

Ping is a command used to determine whether a host is reachable or not it sends ICMP packets to the target host & waits for ICMP packets in response.

1. netstat

Netstat is the command used to display active network connections including both income & outgoing it shows the local address, port & pid of the process associated with each connection.

1. ifconfig

Ifconfig is a command used to display information about all network interfaces currently config on the system or to check IP address.

1. traceroute

Traceroute is a command used to identify the intermediate routers that packets travel between the [local host] & the destination host.

1. nsloop(name server loopup)

Nsloopup command queries the DNS to display the domain & IP address.

6.dig (Domain information groper)

Dig command will be used to display detailed information about DNS records for a specified domain name or IP address.

1. telnet

The telnet command is used to establish a connection to a remote host or server over the network.

1. nmtui

The Nmtui command is used to activate & modify settings in GUI.

 

OSI Layer :

The process of transmitting data between computers. It is divided into **seven layers that work together** to carry out specialized **network functions**, allowing for a more systematic approach to networking.

- DNS Resolution

The process of DNS(Domain Name System)resolution involves converting a hostname  into a computer-friendly IP address (such as 192.168.1.1). 

- TCP(**Transmission Control Protocol** ) handshake

The process of communication between devices over the internet happens according to the current **TCP/IP** suite model(stripped-out version of OSI reference model).



**Physical Layer – Layer 1**

It is responsible for the actual physical connection between the devices. The physical layer contains information in the form of **bits.** It is responsible for transmitting individual bits from one node to the next. 



**Data Link Layer (DLL) – Layer 2**

The data link layer is responsible for the node-to-node delivery of the message. The main function of this layer is to make sure data transfer is error-free from one node to another, over the physical layer.


# Network Layer – Layer 3

The network layer works for the transmission of data from one host to the other located in different networks. It also takes care of packet routing i.e. selection of the shortest path to transmit the packet, from the number of routes available. The sender & receiver’s [**IP address**] are placed in the header by the network layer.

**Transport Layer – Layer 4**

The transport layer provides services to the application layer and takes services from the network layer. The data in the transport layer is referred to as *Segments*. It is responsible for the end-to-end delivery of the complete message. 

**Session Layer – Layer 5**

This layer is responsible for the establishment of connection, maintenance of sessions, and authentication, and also ensures security.

**Presentation Layer – Layer 6**

The presentation layer is also called the **Translation layer**. The data from the application layer is extracted here and manipulated as per the required format to transmit over the network. 

**Application Layer – Layer 7**

These applications produce the data to be transferred over the network. This layer also serves as a window for the application services to access the network and display the received information to the user.

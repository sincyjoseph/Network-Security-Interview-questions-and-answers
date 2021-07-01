# Network-Security-Interview-questions-and-answers

# TCP/IP INTERVIEW QUESTIONS:
![](http://1.bp.blogspot.com/-NZWznbFZdYk/U5YQ12q4UEI/AAAAAAAAAZI/CabndXPDi-A/s1600/tcp.gif)

Explain in short about all 7 layers of OSI
- Application layer = user interface and application
- Presentation layer  = Data conversion and transformation
- session layer  = keep data of diff. application seperately
- transport layer  = end to end connectivity using port numbers.
- network layer = logical addressing like IP address.
- Data link layer = Physical addressing like MAC address.
- Physical layer  = Physical transmission of data using 0's and 1's.

## 1. Explain range of TCP/IP classes
Answer :

![](https://github.com/sincyjoseph/Network-Security-Interview-questions-and-answers/blob/main/ip_Class-1.png)

- CLASS A = 1 to 126
- CLASS B = 128 to 191
- CLASS C = 192 to 223
- CLASS D = 224 to 239 (Multicasting)
- CLASS E = 240 to 255 (Research)

## 2. What are Pvt. IP address ?  
Answer : Pvt. IP are IPs which are not used in Internet or which are not routable in Internet.  They are also called as non-routable IP's. 
- Class A = 10.0.0.0 to 10.255.255.255
- Class B = 172.16.0.0 to 172.31.255.255
- Class C = 192.168.0.0. to 192.168.255.255

## 3. What is function of Router ?
Answer : Router is a device or PC which is used to connect two or more IP networks.

## 4. What is Default Gateway :
Answer : Default gateway is the address of router.

## 5. What is Subnet Mask ?
Answer : Subnet mask is used to differentiate Network ID and Host ID from a given IP address. The default subnet mask are as under
- Class A = 255.0.0.0
- Class B = 255.255.0.0
- Class C = 255.255.255.0

## 6. What is Loopback address ?
Answer : The loopback address is 127.0.0.1. This address is used to check local TCP/IP suite or local machine.

## 7. What protocol is used by PING ?
Answer : Ping uses ICMP(Internet Control Message Protocol)

## 8. What is used of Tracert ?
Answer : Tracert is a to find path information between source and desitnation. It show no. of hops between source and desitination. Tracert also uses ICMP protocol.

## 9. Difference between NetBEUI and TCP/IP
Answer :
| TCP/IP             | NetBEUI               |
| -------------      | -------------         |
| industry standard  | Microsoft propertiery |
| IP address         | NO addressing         |
| supports routing   | Non routable          |
| Large network      | small network         | 
| more confiugration | no configuration      |

## 10. What is full form of PING ?
Answer : Packet Internet Network Gopher

## 11. What is DNS ?
Answer : It is used to resolve FQDN to IP address.

## 12. Types of Zone in DNS ?
Answer : 
- Forward Lookup - it is used to resolve FQDN to IP
- Reverse lookup - it is used to resolve IP to FQDN

## 13. Types of DNS Zone ?
Primary Zone 
Secondary Zone 
AD integrated Zone 
Stub Zone 

## 14. what is NSlookup ?
Answer : it is a tool used troubleshoot DNS related issues.

## 15. What is DHCP ?
Answer: DHCP is used to automatically provide IP address to client computers.

## 16. Explain DHCP 4 packets.
![](https://download.huawei.com/mdl/image/download?uuid=c86f2576de8e450ebf2eb8bd076a7b0b)
- Discover = client sends request for IP.
- Offer = DHCP server send and Offer with IP address.
- Request = if clients accepts the IP it sends a request to DHCP.
- Ack = DHCP server sends ack for the same.

## 17. What is client reservation in DHCP ?
Answer : to reserve a specific IP for a specific machine or host.

## 18. Which port number DHCP uses?
Answer : DHCP uses UDP port number 67 and 68.

## 19. Port numbers for various application and services
There are total 65536 ports available. Below are the list of some well-known ports.
- LDAP  : 389
- Kerberos : 88
- DNS  : 53
- SMTP  : 25
- POP3  : 110
- Telnet  : 23
- NNTP  : 119
- IMAP  : 143
- RPC  : 135
- HTTP  : 80
- HTTPS / SSL : 443
- FTP  : 21
- SNMP : 161 and 162

## 19. What is SNMP ?
Answer : SNMP stands for Simple Network Management Protocol). This protocol is used to monitor and manage network devices like Switches, Routers, Servers, etc. SNMP
uses port UDP port number 161 and 162.

## 20. What is COM ?
Answer : Component Object Model (COM) is Microsoft's object-oriented programming model that defines how objects interact within a single application or between applications.

## 21. What is RPC protocol ?
![](https://book.systemsapproach.org/_images/f05-14-9780123850591.png)
Answer : RPC stands for Remote Procedure Call. It uses port number 135. RPC is an inter-process communication technique that allows client and server software to communicate.

## 22. What is firewall ?
Answer : It is a software used to provide security to your network by not allowing unauthorized access to your Internal network from External users. Eg : PIX firewall, Checkpoint firewall, etc.

## 23. Which protocol is used by ADS for time sync. between PC's?
Answer : SNTP (Simple network time protocol)

## 24. What are the layers of the OSI reference model?
There are 7 OSI layers: 1) Physical Layer, 2) Data Link Layer, 3) Network Layer, 4) Transport Layer, 5) Session Layer, 6) Presentation Layer, and 7) Application Layer.

## 25. What is data encapsulation?
Data encapsulation is the process of breaking down information into smaller, manageable chunks before it is transmitted across the network. In this process that the source and destination addresses are attached to the headers, along with parity checks.

## 26. What is a VPN?

![](https://www.slideteam.net/media/catalog/product/cache/960x720/v/p/vpn_tunnel_structure_architecture_corporate_internet_connection_servers_network_slide03.jpg)
VPN means Virtual Private Network, a technology that allows a secure tunnel to be created across a network such as the Internet. For example, VPNs allow you to establish a secure dial-up connection to a remote server.

## 27. Briefly describe NAT

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/NAT_Concept-en.svg/1024px-NAT_Concept-en.svg.png)

NAT is Network Address Translation. This is a protocol that provides a way for multiple computers on a common network to share a single connection to the Internet.

## 28. What are MAC addresses?
![](https://media.geeksforgeeks.org/wp-content/uploads/mac.jpg)
MAC, or Media Access Control, uniquely identifies a device on the network. It is also known as a physical address or an Ethernet address. A MAC address is made up of 6-byte parts.

## 28. What is SLIP?
SLIP, or Serial Line Interface Protocol, is an old protocol developed during the early UNIX days. This is one of the protocols that are used for remote access.

## 29. What is tracert?
Tracert is a Windows utility program that can use to trace the route taken by data from the router to the destination network. It also shows the number of hops taken during the entire transmission route.

## 30. What is DHCP?
DHCP is short for Dynamic Host Configuration Protocol. Its main task is to assign an IP address to devices across the network automatically. It first checks for the next available address not yet taken by any device, then assigns this to a network device.

## 31. What is the main job of the ARP?
![](https://gsephrioth.github.io/assets/img/TCP-IP/Figure7.3.png)
The main task of the ARP or Address Resolution Protocol is to map a known IP address to a MAC layer address.

## 32. What is TCP/IP?
TCP/IP is short for Transmission Control Protocol / Internet Protocol. This is a set of protocol layers that is designed to make data exchange possible on different types of computer networks, also known as a heterogeneous network.

## 33. How can you manage a network using a router?
Routers have a built-in console that lets you configure different settings, like security and data logging. You can assign restrictions to computers, such as what resources it is allowed access or what particular time of the day, they can browse the Internet. You can even put restrictions on what websites are not viewable across the entire network.

## 34. What is the difference between TCP and UDP?
![](https://www.researchgate.net/profile/Yasir-Ali-9/publication/320114709/figure/tbl1/AS:768560301355010@1560250463196/Comparison-between-TCP-and-UDP.png)

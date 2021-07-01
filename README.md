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
Answer : RPC stands for Remote Procedure Call. It uses port number 135. RPC is an inter-process communication technique that allows client and server software to communicate.

## 22. What is firewall ?
Answer : It is a software used to provide security to your network by not allowing unauthorized access to your Internal network from External users. Eg : PIX firewall, Checkpoint firewall, etc.

## 23. Which protocol is used by ADS for time sync. between PC's?
Answer : SNTP (Simple network time protocol)

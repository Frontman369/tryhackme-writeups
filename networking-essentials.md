# Networking Essentials - TryHackMe Writeup

## Overview
This room introduced essential networking protocols that enable communication across devices and networks. It focused on how systems obtain configuration, resolve addresses, and transmit data across networks.

---

## Objectives
- Understanding the core networking protocols  
- Learning how devices communicate within and across networks  
- Exploring how routing and addressing function in practice  

---

## Concepts Covered
- DHCP (Dynamic Host Configuration Protocol)  
- ARP (Address Resolution Protocol)  
- NAT (Network Address Translation)  
- ICMP (Internet Control Message Protocol)  
- Ping  
- Traceroute  
- Basic routing  

---

## Key Concepts

### DHCP
DHCP automates IP address assignment, allowing devices to join networks without manual configuration. It follows a discover–offer-request–acknowledgment **DORA** process.

---

### ARP
ARP resolves IP addresses to MAC addresses within a local network, enabling devices to communicate at the data link layer. Bridging Layer 3 Addressing to Layer 2.

---

### NAT
NAT translates private IP addresses into a public IP, allowing multiple devices to share a single internet connection.

---

### ICMP, Ping & Traceroute
- **ICMP** is used for diagnostic and error messaging  
- **Ping** checks connectivity between devices  
- **Traceroute** maps the path packets take across a network  

---

### Routing
Routing determines how packets travel from source to destination across networks using routers and routing tables.

---

## Challenges Faced
- Understanding how multiple protocols interact together  
- Visualizing packet flow across different network layers  

---

## Key Takeaways
- Networking relies on multiple protocols working together  
- DHCP and NAT simplify large-scale network management  
- ARP enables communication within local networks  
- ICMP-based tools are essential for troubleshooting  
- Routing is fundamental to how data reaches its destination  

---

## Reflection
This room reinforced how essential networking protocols operate behind the scenes. While these processes are usually invisible during everyday internet use, they form the backbone of all network communication.

Understanding these protocols is critical for both troubleshooting and cybersecurity analysis.

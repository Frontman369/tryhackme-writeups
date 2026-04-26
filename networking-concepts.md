# Networking Concepts - TryHackMe Writeup

## Overview
This room, part of Cyber Security 101, revisited and reinforced core networking fundamentals including the OSI model, TCP/IP model, IP addressing, subnetting, and key transport protocols.

It served as a strong refresher of concepts introduced earlier in the Pre Security Path while also introducing deeper networking topics.

## Tools & Concepts Used
- OSI Model  
- TCP/IP Model  
- IP addressing (IPv4)  
- Subnetting concepts  
- TCP vs UDP  
- Encapsulation  
- Telnet  

---

## Key Concepts

### OSI & TCP/IP Models
The OSI and TCP/IP models explain how data moves across networks in layered structures. This helps in understanding how communication occurs between devices over the internet.

---

### 📡 Public vs Private IP Addresses

#### Private IP Ranges:
- `10.0.0.0 – 10.255.255.255`
- `172.16.0.0 – 172.31.255.255`
- `192.168.0.0 – 192.168.255.255`

These are used within internal networks and are not directly accessible from the internet.

#### Public IP Addresses:
Any IP address outside the private ranges is considered public and is routable on the internet (e.g., `8.8.8.8`).

Understanding this distinction is important to avoid targeting unreachable internal systems during security assessments.

---

### TCP vs UDP

- **TCP (Transmission Control Protocol)**  
  Reliable, connection-based communication with error checking.

- **UDP (User Datagram Protocol)**  
  Faster, connectionless communication without guaranteed delivery.

---

### Encapsulation
Encapsulation refers to the process of wrapping data with protocol information as it moves through each layer of the network stack.

---

### Telnet
Telnet is a protocol used for remote communication with devices, often used for testing and basic network interactions.

---

## Challenges Faced
- Recalling previously learned networking concepts  
- Differentiating between similar protocol behaviors  
- Understanding how layered models interact in practice  

---

## Key Takeaways
- Networking models (OSI and TCP/IP) are essential for understanding data flow  
- Correct identification of IP address types is critical in security analysis  
- TCP and UDP serve different communication needs  
- Encapsulation explains how data is transmitted across layers  
- Strong foundational knowledge is necessary for advanced cybersecurity topics  

---

## Reflection
This room served as a strong refresher of core networking concepts. While most topics were familiar from earlier learning, revisiting them helped reinforce understanding and improve clarity.

It highlighted the importance of mastering fundamentals, as they form the base for more advanced cybersecurity concepts.

---

## Notes
- Focus was on reinforcing foundational networking knowledge  
- No exploitation or advanced tooling was involved  
- This room strengthens core understanding required for future security analysis  

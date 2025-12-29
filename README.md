# Basic Switching and DHCP

## 📌 Project Overview
A Cisco Packet Tracer project implementing a secure multi-VLAN enterprise network with inter-VLAN routing, DHCP, SSH management, and Layer 2 security features such as DHCP Snooping, DAI, BPDU Guard, and port security.

## 🧱 Network Topology
- 1 Router (Router-on-a-Stick)
- 1 Core Switch
- 3 Access Switches
- End devices per department

## 🗂 VLAN & IP Addressing Scheme

| VLAN | Department | Network |
|----|----|----|
| 10 | Accounting | 192.168.1.0/24 |
| 20 | HR | 192.168.2.0/24 |
| 99 | IT / Management | 192.168.99.0/24 |
| 69 | unused port | 

## ⚙️ Implemented Technologies

### Routing & Services
- Router-on-a-Stick
- DHCP per VLAN
- Subinterfaces
- SSH remote access (IT VLAN only and one far away)

### Switching & Security
- VLAN Trunking (802.1Q)
- STP
- BPDU Guard
- DHCP Snooping
- Dynamic ARP Inspection (DAI)
- Port Security
- VLAN Hopping Attack Prevention

## 🔐 Security Highlights
- DHCP Snooping prevents rogue DHCP servers
- DAI protects against ARP spoofing
- BPDU Guard prevents STP attacks
- SSH access restricted to ALL VLAN EXCEPT VLAN 99 (IT) and ONE IP ADDRESS

## 🧪 Testing & Verification
- DHCP IP assignment verified per VLAN
- Inter-VLAN communication is successful
- Unauthorized access blocked
- Security features validated using test scenarios

## 🛠 Tools Used
- Cisco Packet Tracer
- Cisco 2911 Router
- Multilayer 3650-24ps
- Cisco 2960 Switch
  


## 👨‍💻 Author
**Angelo Adame**  
Aspiring Network Engineer | CCNA Track

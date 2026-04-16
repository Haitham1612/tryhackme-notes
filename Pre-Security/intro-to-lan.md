# Intro to LAN

**Room:** Intro to LAN (Pre Security / Networking Fundamentals)  
**Date Completed:** 16 April 2026  
**Difficulty:** Easy  
**Link:** https://tryhackme.com/room/introtolan

## Task 1: Introducing LAN Topologies

### Star Topology
- Devices connect directly to a central device (switch or hub).
- Most common in modern networks.
- **Advantages**: Scalable, easy to add devices, one device failure doesn't crash everything.
- **Disadvantages**: Expensive (more cabling + hardware), single point of failure at the central switch, higher maintenance as it grows.

### Bus Topology
- All devices share one backbone cable.
- **Advantages**: Cheap and simple to set up.
- **Disadvantages**: Single point of failure (backbone breaks = whole network down), gets slow with traffic, very hard to troubleshoot.

### Ring Topology
- Devices form a loop, data travels in one direction.
- **Advantages**: Less cabling, no major bottlenecks like Bus.
- **Disadvantages**: One break takes down the entire network, data can pass through many devices (inefficient).

### Switches
- Smart devices that connect multiple endpoints via Ethernet ports.
- Learn MAC addresses and send traffic only to the correct port (much better than hubs).
- Used in offices/schools for larger networks.

### Routers
- Connect different networks and route traffic between them.
- Create redundancy when multiple paths exist (if one link fails, traffic can take another path).

**Key Takeaway from Task 1:**
Star topology dominates today because of reliability and scalability. Bus and Ring are mostly outdated due to single points of failure — important for understanding network resilience and attack surfaces.

## Task 2: A Primer on Subnetting
(Write your summary here when you finish it)
- Main concepts...
- Key formulas or examples...
- Takeaway...

## Task 3: ARP
(When you do it)
- What ARP does...
- How it works (request/reply)...
- Security implications (e.g. ARP poisoning)...

## Task 4: DHCP
(When you do it)
- How devices get IP addresses automatically...
- DORA process...
- Takeaway...

## Task 5: Continue Your Learning - OSI Model
(When you do it)
- Quick recap of the 7 layers...
- Which layers we care about most in security...
- Takeaway...

## Overall Room Takeaways
- This room gave me solid fundamentals on how local networks are designed and how devices communicate.
- Understanding topologies + protocols like ARP/DHCP is crucial for network security (e.g. spotting misconfigurations or attacks).
- Helped me see why switches and proper routing matter for performance and reliability.

**Screenshots added:**
- LAN topologies diagrams
- Any subnetting examples or questions I answered

**Flags / Answers:** (optional — you can list them if you want, but many people skip exact flags)

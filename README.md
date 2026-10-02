*This project has been created as part of the 42 curriculum by anashwan*

**[You can view my notes that cover the concepts in more detail here.](https://ahmad-nashwan.github.io/articles/networking-fundamentals/)**

## Description

NetPractice is a practical exercise designed to introduce the basics of computer networking. The goal is to configure IP addresses, subnet masks, default gateways, and other network settings until the network operates correctly.

### Networking Concepts Studied

- **Routers and switches** — A switch connects a group of computers that are close to each other, using MAC addresses to send data between devices on the same local wire. A router operates at the Network layer and thinks in IP addresses, letting your data leave that wire and find its way across other networks.
- **OSI and TCP/IP layers** — Data doesn't just go from your laptop to a server; it gets wrapped, layer by layer, handed down, sent, and unwrapped in reverse. Top to bottom: Application (what you actually see), Transport (which program it's for), Network (how it crosses the internet), Data Link (how it moves on the local wire), Physical (raw signal).
- **ARP** — Because your laptop doesn't know the exact MAC address it needs to build a frame, it sends a broadcast message asking "Who has this IP address?"
- **Subnet masks** — The subnet mask is the dividing line that tells the computer exactly where the Network Bits end and the Host Bits begin. We drag that line to the right to borrow Host Bits and create smaller, custom networks.
- **DHCP** — Hands out an IP address, the subnet mask, the default gateway, and the DNS server automatically using a 4-step broadcast handshake called DORA.
- **DNS** — Exists because humans remember website names, but routers only understand IP addresses.
- **TCP and UDP** — TCP establishes a dedicated, tracked conversation using a 3-way handshake. UDP throws out the session overhead for pure speed, making it the right choice when a late packet is worse than a missing one.

### AI Usage

AI was used to debug errors in the configuration files and helping me study.

*This project has been created as part of the 42 curriculum by anashwan*

## Description

NetPractice is a practical exercise designed to introduce the basics of computer networking. The project provides a training interface with 10 levels of network configuration challenges. Each level presents a non-functioning network diagram, and the goal is to configure IP addresses, subnet masks, default gateways, and other network settings until the network operates correctly.

## Instructions

1. Download the project files and extract them into a folder of your choice.
2. Run the training interface:
   ```bash
   ./run.sh
   ```
   If `run.sh` does not work, you can start a local server manually:
   ```bash
   python3 -m http.server 49242
   ```
   Then open `http://localhost:49242` in your web browser.

3. Enter your login in the training interface to use your personal configuration.
4. For each level, modify the unshaded fields to configure the network correctly.
5. Use the **[Check again]** button to verify your configuration.
6. Once a level is completed, click **[Get my config]** to export your configuration file.
7. Repeat for all 10 levels.

### Submission

- Export 10 configuration files (one per level) using the **[Get my config]** button.
- Place all 10 files at the root of your Git repository.
- During the defense, you must successfully complete three random levels within a time limit.
- No external tools are allowed during evaluation; a simple calculator such as `bc` is tolerated.

## Resources

### Networking Concepts Studied

- **TCP/IP addressing** — understanding IP addresses, network bits, and host bits
- **Subnet masks** — CIDR notation, bitwise AND operations, and calculating network IDs
- **Default gateways** — how devices route traffic outside their local network
- **Routers and switches** — the role of routers at the Network layer and switches at the Data Link layer
- **OSI and TCP/IP layers** — the 5-layer TCP/IP model and the 7-layer OSI model, including encapsulation and decapsulation
- **ARP** — Address Resolution Protocol for resolving IP addresses to MAC addresses on the local network
- **DHCP** — Dynamic Host Configuration Protocol and the DORA process
- **DNS** — Domain Name System resolution process
- **TCP and UDP** — transport layer protocols, the 3-way handshake, and when to use each

### References

- [Networking Fundamentals — undefined_notes](https://undefined-notes.vercel.app/articles/networking-fundamentals/) — my own study notes written while completing this project, covering the OSI/TCP-IP models, encapsulation, ARP, routing, subnetting, DHCP, DNS, and TCP/UDP in depth.
- [GeeksforGeeks — Subnetting in Computer Networks](https://www.geeksforgeeks.org/computer-networks/subnetting-in-computer-network/) — subnet mask and CIDR calculation walkthrough.
- [GeeksforGeeks — DHCP (Dynamic Host Configuration Protocol)](https://www.geeksforgeeks.org/computer-networks/dynamic-host-configuration-protocol-dhcp/) — DORA process explained.
- [GeeksforGeeks — ARP (Address Resolution Protocol)](https://www.geeksforgeeks.org/computer-networks/address-resolution-protocol-arp/) — how IP-to-MAC resolution works.
- [GeeksforGeeks — OSI Model](https://www.geeksforgeeks.org/computer-networks/layers-of-osi-model/) — layer-by-layer breakdown of the OSI model.
- [subnetting.net](https://subnetting.net/) — interactive subnetting practice tool used to drill exercises before evaluation.

### AI Usage

AI was used to debug errors in the configuration files and helping me study.

# Weeks 1 & 2: Networking & Subnetting Foundations

## Week 1: Computer Networking Basics
* **Core Concepts:** Learned how devices communicate using Hubs, Switches, and Routers.
* **The 7 Layers of the OSI Model:**
  * *Layer 7: Application* - Where network applications operate (HTTP, FTP). Web app attacks happen here.
  * *Layer 6: Presentation* - Handles data formatting, compression, and encryption (SSL/TLS).
  * *Layer 5: Session* - Manages and controls connections between applications.
  * *Layer 4: Transport* - Manages data transfer protocols like TCP (reliable) and UDP (fast).
  * *Layer 3: Network* - Determines data routing using IP Addresses. Routers operate here.
  * *Layer 2: Data Link* - Handles physical addressing using MAC Addresses. Switches work here.
  * *Layer 1: Physical* - The physical hardware, cables, and electrical signals.

## Week 2: IP Addressing & Subnetting ("You Suck at Subnetting")
* **Core Concepts:** Mastered IPv4 structures, Subnet Masks, and Decimal-to-Binary conversion. 
* **Network Segmentation:** Learned how to physically cut a massive network into smaller, isolated pieces.
* **Security Benefit:** Using a `/25` subnet mask (`255.255.255.128`) splits a network into two distinct zones. This ensures that if an attacker compromises a computer in the IT subnet, they cannot easily access the HR subnet without passing through a router or firewall where security rules can block them.

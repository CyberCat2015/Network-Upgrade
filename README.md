# Network-Upgrade
Welcome to my first documented cybersecurity home lab project.
This repo is part of my ongoing journey as a cybersecurity analyst, and I’m sharing it both to document my experience and to help others looking to improve their own home networks. In this project, I’m replacing a standard commercial router with a dedicated firewall/router powered by pfSense. This gives me more visibility and control over how my network is structured and secured.

Below you’ll find the project’s goals, the hardware I used, a basic network design, current status, and future enhancements I plan to implement in the next phase.

🛠️ Project Goals
- Replace commercial all-in-one router with a dedicated firewall/router using pfSense on a Protectli FW6D.

- Implement proper network segmentation using VLANs to isolate guest and IoT traffic from the main network.

- Improve overall visibility and control of network traffic for learning and security purposes.

- Lay the foundation for a future cybersecurity lab environment.

🔧 Hardware Used
- Protectli Vault FW6D (8 GB ram / 240 GB SSD) – Running pfSense CE

- Ubiquiti UniFi Switch Lite 16 PoE – Managed switch with VLAN support

- Ubiquiti UniFi U6 Pro – Dual-band Wi-Fi 6 access point

- (Optional future) Custom-built server – Will host Security Onion and various VMs for testing

🗺️ Basic Network Design
- pfSense handles DHCP, VLANs, and acts as the main gateway/firewall

- VLAN A – Main/Trusted network

- VLAN B – Guest network

- VLAN C- IoT devices

- UniFi U6 Pro broadcasts separate SSIDs for the Guest, Main, and IoT networks. 

- UniFi switch enforces VLAN separation between wired devices

📊 Project Status
🔲 Hardware acquisition

🔲 pfSense installed

🔲 VLANs configured

🔲 UniFi switch and AP setup

🔲 Basic segmentation testing

✅ Documentation in progress (this repo)

🔮 Future Enhancements
- Deploy a home server with Security Onion to monitor and analyze network traffic

- Add virtual machines for hands-on attack simulation and defensive analysis

- Automate log collection and alerting for security events

- Explore integration with tools like Zeek, Suricata, and ELK stack


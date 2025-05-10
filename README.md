# Network-Upgrade
Upgrading my home network with pfSense, network segmentation (VLANS), and Ubiquiti hardware for improved security and performance.

Goals
- Replace consumer-grade router with pfSense firewall
- Implement VLAN-based network segmentation
- Isolate IoT and guest devices from core network
- Improve visibility, control, and security

Hardware
- Firewall: Protectli FW6D running pfSense
- Switch: Ubiquiti Switch Lite 16 PoE (managed)
- Wi-Fi: Ubiquiti U6 PRO Dual-Band Wi-Fi 6 AP

Network Design
- Main LAN: Trusted devices (PCs, NAS, etc.)
- Guest VLAN: Segmented access for visitors
- IoT VLAN: Isolated for smart devices
- Management VLAN (optional): Admin access to infrastructure

Status

🛠️ Hardware setup – not complete

⚙️ pfSense installation and configuration – not complete

🔧 VLAN setup and testing – not complete

📋 Documentation and diagrams – coming soon

Future Enhancements
- Security Onion Deployment: Set up a dedicated server with Security Onion for network monitoring, intrusion detection, and security event analysis.
- Cybersecurity Testing VMs: Host various VMs for testing and analysis (e.g., Kali Linux, Metasploit, etc.) for hands-on penetration testing, attack simulations, and defense strategies.
- IDS/IPS Integration: Implement network-based intrusion detection systems (IDS) or intrusion prevention systems (IPS) for real-time monitoring and threat mitigation.
- Logging & Monitoring: Integrate ELK stack or a similar tool to aggregate logs from various devices and services for deeper analysis.
- VPN Access: Configure a VPN server for secure remote access to your home network and lab environment.


Author: Paul Corrao

Contact: https://www.linkedin.com/in/paul-corrao/

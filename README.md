# Simple DHCP Practical - Cisco Packet Tracer Lab
This repository contains a Cisco Packet Tracer simulation file (`DHCP-Practical.pkt`) that demonstrates how to configure and test **Dynamic Host Configuration Protocol (DHCP)** in a small network.
---
## 📂 File Included
- **DHCP-Practical.pkt** → Packet Tracer file for DHCP server-client configuration.
---
## 📝 Lab Overview
In this lab:
- A DHCP server is configured to automatically assign IP addresses to clients.
- Devices such as PCs, Switches, and Routers are connected in a simple topology.
- DHCP eliminates the need for manual IP configuration.
---
## ⚙️ Steps to Run
1. Download and install **Cisco Packet Tracer** (version 8.0 or later recommended).
2. Clone this repository or download the `.pkt` file directly.
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
or simply click Download ZIP.
3. Open DHCP-Practical.pkt in Packet Tracer.
4. Run the simulation and verify:
PCs receive IP addresses automatically.
DHCP leases are assigned properly.

🔧 Key Commands Used (Cisco Router)
Router> enable

Router# configure terminal

Router(config)# ip dhcp pool name(LAB) 

Router(dhcp-config)# network 10.0.0.0 255.0.0.0

Router(dhcp-config)# default-router 10.0.0.1

Router(dhcp-config)# dns-server 8.8.8.8

Router(dhcp-config)# exit

Router(config)# ip dhcp excluded-address 10.0.0.1

📖 Learning Objectives

Understand DHCP server configuration.
Learn how IP addresses are leased to clients dynamically.
Troubleshoot DHCP issues in Packet Tracer.

🤝 Contributing

Feel free to fork this repo and improve the lab (e.g., add multiple VLANs, routers, or extra services).

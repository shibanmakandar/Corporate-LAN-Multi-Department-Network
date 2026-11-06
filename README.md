# Corporate-LAN-Multi-Department-Network
🌐 Designed a Corporate LAN network connecting Engineering, Sales, and Support departments using VLSM subnetting, Cisco routers, and switches. 🚀 Implemented point-to-point WAN connectivity and RIPv2 dynamic routing in Cisco Packet Tracer, ensuring efficient IP allocation, secure communication, seamless connectivity, scalability across departments.

🌐 Corporate LAN Setup with Multiple Departments

🚀 Project Overview

This project demonstrates the design, implementation, and configuration of a Corporate Local Area Network (LAN) connecting three different departments: 🏢 Engineering, 💼 Sales, and 🛠️ Support. The network is designed and simulated using Cisco Packet Tracer, providing seamless communication between departments through efficient IP addressing and dynamic routing.

🧩 Key Features & Technologies

- 🌐 VLSM Subnetting: Efficiently divides the "192.168.10.0/24" network into smaller subnets based on departmental host requirements.
- 🏢 Departmental Network Segmentation: Separate subnets for Engineering, Sales, and Support to improve network management and traffic control.
- 🔗 Point-to-Point WAN Connection: Establishes communication between two routers using a serial WAN link with a "/30" subnet.
- 📡 RIPv2 Dynamic Routing: Automatically exchanges routing information between routers, enabling communication across different networks.
- 🔐 Improved Network Management: Uses separate broadcast domains and passive interfaces for better traffic control.
- 💻 Cisco Packet Tracer Simulation: Builds and tests the complete network topology with routers, switches, PCs, and a laptop.

📊 IP Addressing & Subnet Allocation

Department| Network| Subnet Mask| Usable Hosts
🏢 Engineering| 192.168.10.0/26| 255.255.255.192| 62
💼 Sales| 192.168.10.64/27| 255.255.255.224| 30
🛠️ Support| 192.168.10.96/28| 255.255.255.240| 14
🔗 WAN Link| 192.168.10.112/30| 255.255.255.252| 2

⚙️ Network Implementation

The network uses two Cisco 2901 routers, three Cisco 2960 switches, and multiple end devices. Each department is connected through its respective router interface, while the two routers communicate through a serial connection.

RIPv2 is configured with "no auto-summary" to support VLSM subnetting and ensure that all departmental networks are advertised correctly.

🧪 Testing & Verification

The network is tested using various Cisco IOS commands and connectivity checks:

- ✅ "ping" – Verifies communication between departments.
- 🔍 "tracert" – Displays the path taken by network packets.
- 📡 "show ip route" – Checks dynamically learned routing information.
- ⚙️ "show ip interface brief" – Verifies interface status.
- 🔄 "show ip protocols" – Checks RIPv2 configuration.

🎯 Project Objectives & Benefits

- 📌 Efficient utilization of IP addresses.
- 🔒 Better departmental network segmentation.
- ⚡ Reduced broadcast traffic.
- 🌍 Seamless communication between departments.
- 🔧 Simplified troubleshooting and network administration.
- 📈 Scalability for future network expansion.

🏆 Final Outcome

Successfully designed and simulated a multi-department corporate LAN using VLSM subnetting, point-to-point WAN connectivity, and RIPv2 dynamic routing. All departments can communicate with each other, while 140 IP addresses remain available for future expansion.

💡 Skills Demonstrated: Computer Networking | Cisco Packet Tracer | IP Addressing | VLSM | Subnetting | Router Configuration | Switch Configuration | WAN Connectivity | RIPv2 | Network Troubleshooting

🔥 Building efficient, scalable, and interconnected corporate networks! 🌐🚀

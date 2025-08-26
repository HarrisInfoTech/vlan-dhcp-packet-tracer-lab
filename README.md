# VLAN-Segmented Network with DHCP – Cisco Packet Tracer Lab

## 🖥️ Project Overview
Designed and configured a VLAN-segmented network in Cisco Packet Tracer. Each department (IT, HR, Sales, Marketing) operates within its own subnet. Implemented DHCP on the router using router-on-a-stick configuration to dynamically assign IP addresses to client devices.

---

## 🧱 Network Components
- 1 Router (Cisco 2911)
- 1 Switch (Cisco 2960)
- 8 PCs (2 per department)
- 4 VLANs:
  - VLAN 10 – IT: 192.168.10.0/24
  - VLAN 20 – HR: 192.168.20.0/24
  - VLAN 30 – Sales: 192.168.30.0/24
  - VLAN 40 – Marketing: 192.168.40.0/24

---

## ⚙️ Key Configurations

### 🔸 Switch Configuration
```
[See `configs/router-config.txt` for full command list]
```

### 🔸 Router Configuration & DHCP Setup
Each VLAN is configured with its own sub-interface and DHCP pool on the router.

---

## 📷 Network Topology
![Network Topology](diagrams/diagramstopolgy.png)

---

## ✅ Skills Demonstrated
- VLAN and port assignment
- Router-on-a-stick configuration
- DHCP pool setup and exclusion
- Inter-VLAN communication
- Network troubleshooting (ping, IP config)



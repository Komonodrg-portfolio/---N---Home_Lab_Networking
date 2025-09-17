### [Cybersecurity](https://github.com/Komonodrg-portfolio/Cybersecurity) | [Networking](https://github.com/Komonodrg-portfolio/Networking) | [Data Science (AI)](https://github.com/Komonodrg-portfolio/AI) | [Media Creation](https://github.com/Komonodrg-portfolio/MediaCreation) | [Mission](https://github.com/Komonodrg-portfolio/Mission/)

---
---

# 🏠 Home Network Lab Creation using EVE-NG

This project demonstrates a simulated enterprise-like network lab built using **EVE-NG (Emulated Virtual Environment Next Generation)**. It's designed to emulate a small business or advanced home network, complete with routers, switches, firewalls, and virtual hosts.  With a labtop of 16GB  (recommended) of ram, this platform allows training from anywhere in the world.

---

## 📌 Goals
To illustrate a cost effective platform to  allow for the practice and self study in Network Engineering via providing the ability to:

- Design and emulate a complex network topology
- Practice configuration of Cisco routers, Layer 2/3 switches, and firewalls
- Test routing protocols (OSPF, EIGRP, BGP)
- Implement VLANs and inter-VLAN routing
- Simulate internet connectivity with NAT/PAT
- Prepare for CCNA/CCNP certification as well as network automation
- **Can even be expanded to allow for cyber security training**

---

## 🧰 Tools & Technologies

| Tool       | Purpose                              |
|------------|--------------------------------------|
| EVE-NG     | Network Emulation Platform           |
| Cisco IOU / Dynamips | Router & Switch Emulation         |
| pfSense / OPNsense    | Open-source Firewall/Router          |
| Linux  / Windows VMs  | Host Simulation                      |
| Wireshark  | Packet Capture and Analysis          |

---



---

## 🔧 Setup Instructions

### 1. Install EVE-NG
Follow the [official EVE-NG installation guide](https://www.eve-ng.net/index.php/documentation/) or run it in VMware/VirtualBox on Linux Mint.

### 2. Upload Images
Ensure you have the appropriate Cisco and pfSense images loaded into EVE-NG. Add them via the `/opt/unetlab/addons/qemu` path.

### 3. Import or Recreate the Lab
You can:
- Import the provided `.unl` lab file (if included), or
- Recreate the topology manually in EVE-NG using the included topology diagram and configs.

### 4. Connect EVE-NG to Internet
To simulate external access (e.g., software updates on Ubuntu), configure a cloud interface to your host system’s bridge or NAT.

---

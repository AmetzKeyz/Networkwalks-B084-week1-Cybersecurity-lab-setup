# Cybersecurity-Lab-Setup

A virtualized network lab for ethical hacking, penetration testing, and security analysis — including architecture, setup guide, and configurations.

---
## 🛠️ Environment Overview

The lab environment is built using Oracle VirtualBox and consists of virtual machines configured across local and internal networks:

- **Main Host OS**: Serves as the target workstation environment.
- **Kali Linux**: Serves as the primary platform for security auditing and penetration testing.
- **VirtualBox Network Adapters**: Configured with NAT and Internal Network modes to simulate real-world subnet isolation and communication.

---

## 📸 Setup Screenshots & Visual Guide

A breakdown of the key screenshots included in this project:

1. **`1-Screenshot-title-image.png`**: High-level architecture diagram showing the overall VirtualBox lab structure, subnets, and host-guest topology.
2. **`screenshot-network-settings-1.png`**: VirtualBox Manager interface highlighting the virtual network adapter configurations.
3. **`screenshot-kali-linux.png`**: Active Kali Linux desktop environment running inside the virtualized setup.
4. **`screenshot-kali-network-settings.png`**: Network configuration inside Kali Linux showing custom IP assignment and subnet settings.

---

## ⚙️ Configuration Steps

1. **Virtual Machine Creation**: Provision Windows 10 and Kali Linux instances in VirtualBox.
2. **Network Interface Setup**: Configure network adapters (NAT / Internal Network / Host-Only) for each VM based on its role.
3. **IP Configuration**: Assign and verify internal IP addresses in Kali Linux to establish communication with target hosts.
Downloaded & Installed.


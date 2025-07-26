# Home Lab SOC & Network Security Environment

## Project Overview

Multi-purpose cybersecurity and networking home lab featuring a custom MERN stack bioinformatics application that serves as both a functional tool and controlled vulnerable environment for penetration testing.

**Key Features:**
- Network segmentation with VLANs
- SOC monitoring setup
- Penetration testing environment
- IoT security research testbed
- Linux server infrastructure

## Network Architecture

### Hardware

| Device | Specifications | Role |
|--------|---------------|------|
| **Desktop Workstation** | i9 CPU, Security Onion, 32GB RAM | SOC Monitoring Station |
| **Asus TUF Laptop** | Kali Linux VM | Attack Vector/Penetration Testing |
| **Dell PowerEdge R220** | Linux Server 24.04.2 | Application Server |
| **Lenovo ThinkCenter** | Linux Server | Secure Jumpbox |

### Network Equipment

- **TP-Link TL-SG108E Managed Switch** - VLAN segmentation and traffic monitoring
- **Asus RT-AX58U Router** - VPN server and firewall rules

### IoT Testing Environment

- CCTV cameras, tablets, and Arduino devices for IoT security research

## Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **File Processing:** Multer for bioinformatics file uploads

## Security Implementation

### Network Segmentation
- **Management VLAN:** Administrative access
- **Production VLAN:** Application and database servers
- **Testing VLAN:** Isolated penetration testing environment
- **IoT VLAN:** Quarantined IoT device network

### Security Controls
- Jumpbox access for server management
- VPN integration for remote access
- Firewall rules and traffic monitoring
- Real-time threat monitoring

---

**Status:** Active Development

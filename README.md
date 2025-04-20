# WAN-OSPF-Route
Complete configuration of enterprise network with 9 Cisco devices including
Here's your updated technical documentation with modified emojis:

# 🔌 Cisco Enterprise Network - Technical Documentation

![net-2](https://github.com/user-attachments/assets/fcb3fb30-aea0-4848-a31b-803054c62d54)


## 🔍 Project Overview
Complete configuration of enterprise network with 11 Cisco devices including:
- 3 Cisco 2901 routers
- 6 Catalyst 2960 switches
- User: admin
- Password: P@ssw0rd

## 📋 Device Specifications

### 🖥️ Routers
| Name | Model | IP Address | Role |
|------|-------|------------|------|
| RU-1 | 2911 | 172.62.20.1 | Site A Router |
| RU-2 | 2911 | 172.62.20.5 | Site B Router |
| Internet | 1941 | 172.168.1.2 | Site C Router |

### 🔄 Switches
| Name | Model | IP Address | Location |
|------|-------|------------|----------|
| SWL3-1 | 3560 | 192.168.200.1 | Site A | 
| SWA-1 | 2960 | 192.168.200.2 | Site A |
| SWA-2 | 2960 | 192.168.200.3 | Site A |
| SWL3-2| 3560 | 192.168.200.11 | Site B |
| SWA-3 | 2960 | 192.168.200.10 | Site B |
| SWA-4 | 2960 | 192.168.200.12 | Site B |

## 🏷️ VLAN Architecture 
### VLAN Allocation Table
| VLAN ID | Name | Purpose | Associated Devices |
|---------|------|---------|--------------------|
| 1 | Default | Unused | All switches |
| 20 | Computers | Workstations | All switches |
| 25 | Servers | Server network | All switches |
| 200 | Management | Device management | All devices |


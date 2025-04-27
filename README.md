# Network Infrastructure & Security Project

## Overview
This project focuses on designing and implementing a secure, high-availability network infrastructure connecting a branch office to headquarters via a Site-to-Site VPN.  
It includes FortiGate firewall deployment, Active Directory Domain Services (AD DS) setup, network segmentation, and redundancy planning.

## Project Objectives
- Establish a secure Site-to-Site VPN connection between branch and HQ.
- Deploy redundant network infrastructure using OSPF dynamic routing, HSRP, and VLAN segmentation.
- Set up FortiGate firewall policies and HA (High Availability) configuration for uptime assurance.
- Configure a Windows Server Domain Controller with DHCP, DNS, and user account management.
- Implement security best practices across both the network and server environments.

## Technologies Used
- **Networking Devices:** Routers and Switches (via PNETLab)
- **Firewall:** FortiGate (Version 7.2)
- **Server:** Windows Server 2019 (Active Directory Domain Services, DHCP, DNS)
- **Protocols and Services:**  
  - Site-to-Site VPN (IPSec)  
  - OSPF (Routing)  
  - HSRP (Gateway Redundancy)  
  - VLANs and Inter-VLAN Routing  
  - DHCP, DNS

## Key Configurations
- Created multiple VLANs for departments and implemented Inter-VLAN routing.
- Configured OSPF between routers for dynamic route learning.
- Enabled HSRP between core routers for gateway redundancy and failover.
- Set up FortiGate Firewalls with:
  - Firewall security policies
  - Remote Access VPN
  - Site-to-Site VPN
  - High Availability (HA) clustering
- Installed and configured Windows Server 2019 with:
  - Active Directory Domain Services (AD DS)
  - DHCP server role
  - DNS server role
  - User account creation and network drive mapping

## Project Structure
- **/Backups:** Contains backup configuration files for routers, switches, and FortiGate devices.
- **/Diagrams:** Includes network topology and VPN design diagram.
- **/Screenshots:** Key screenshots of AD setup.

## How to Use
1. Load the provided device configuration backups into PNETLab.
2. Reboot devices and verify network topology and routing table convergence (OSPF).
3. Test Site-to-Site VPN connectivity between branch and HQ.
4. Validate Active Directory functionality: user login, DHCP leases, DNS resolution.
5. Test failover scenarios (HSRP and FortiGate HA).

## Skills Demonstrated
- Enterprise-level network design and implementation
- Firewall configuration and VPN deployment (FortiGate)
- Server administration (Windows Server 2019, AD DS, DHCP, DNS)
- High Availability and redundancy setup
- Network troubleshooting and validation

## Author
**Sara Hesham**  
- [LinkedIn](https://www.linkedin.com/in/sara-hesham-238b98287/)  
- [GitHub](https://github.com/Sa-Ra24)

---

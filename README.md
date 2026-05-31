# Computing & Network Infrastructure Design and Defense

## Overview
The goal was to design, build, secure, defend, and monitor a computing and network infrastructure simulating a small-to-medium organization, operating under air-gap lab constraints. Our team created a fictional grocery retailer, FoodBar, and built out its full IT environment across two segmented VLANs — one for servers and one for clients — hosted on a physical Proxmox hypervisor. The infrastructure included Active Directory, primary and secondary DNS, DHCP, NTP, a web server, file server, print server, Microsoft SQL Server database, and a Wazuh SIEM deployed as a Docker container for centralized monitoring and detection. Security controls included CIS benchmark hardening, Group Policy enforcement, OpenVPN for remote access, host-based firewalls, and MITRE ATT&CK-mapped detection rules.

---

## My Role
- Sourced and physically transferred all ISOs and software into the air-gapped lab environment, then installed and configured all virtual machines in Proxmox to get the project started
- Configured the Primary DNS server on the Windows Server 2022 domain controller, including all required DNS records and integration with Active Directory
- Set up both Windows client workstations, including domain joining, RDP enablement, and network configuration
- Set up both Linux (Ubuntu) client workstations, including domain joining, SSH enablement, and network configuration
- Handled all networking setup for the systems above, including IP addressing, VLAN assignment, and connectivity verification
- Collaborated with the team on security controls, MITRE ATT&CK analysis, and overall infrastructure hardening

---

## Skills & Techniques
- Deploying and configuring enterprise infrastructure services including Active Directory, DNS, and virtualized systems in Proxmox
- Setting up and securing Windows and Linux endpoints with RDP, SSH, domain integration, and host-based network configuration
- Applying security hardening practices across a mixed Windows/Linux environment using CIS benchmarks, Group Policy, and centralized SIEM monitoring
- Operating within an air-gapped lab environment, including manually sourcing and transferring software, resolving package dependencies offline, and building infrastructure without internet access

---

> **Note:** The full group report, final presentation, and network inventory can be found in this repository.

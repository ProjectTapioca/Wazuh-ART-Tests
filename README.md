# Atomic-Red-Team-Tests (Summary)
This project is based on [Wazuh: Emulation of ATT&CK Techniques](https://wazuh.com/blog/emulation-of-attck-techniques-and-detection-with-wazuh/).
I demonstrate the components of basic network configuration and using Wazuh to ingest logs generated from Atomic Red Team Tests. Everything performed was completed on my homelab stack.

## Objective
The main objective is to create custom rules that would detect and log attack vectors generated from the Atomic Tests. Other objectives involved understanding sysmon, xml configuration files, and fixing errors or using workarounds when encountering errors.

## Equipment
Edgerouter-x-sfp
Cisco Catalyst 2960-C
Proxmox Server (PC)
Wazuh Virtual Machine
Windows 11 Virtual Machine

### Network
[Network Diagram](https://github.com/ProjectTapioca/Wazuh-ART-Tests/blob/main/Network%20Diagram.png)
A basic firewall configuration was setup in the router, along with two subnets for the two VLANs used.

### Wazuh
Installed on a virtual machine running Ubuntu 22.04

### Atomic Host
Installed on a Windows 11 virtual machine

### Learning Lessons
Errors that occured and what I learned

# Wazuh_SOC_Lab
This is my Wazuh SOC lab repo. This project is documenting my process of deploying, configuring and implementing various security tools.

# Overview
The purpose of this project is to demonstrate my knowledge regarding end-to-end deployment and configuration of various security tools using Wazuh SIEM/XDR, PFsense firewall and Suricata IDS

# Lab Architecture
The lab is built using VMware VMs and includes the following components:
- Wazuh Server v4.14.6: Runs the Wazuh Manager, Indexer and Dashboard. Collects and correlates logs from various agents
- Windows Endpoint (Windows 11 Pro):
- Attacker Machine
- pfSense Firewall
- Suricata IDS/IPS

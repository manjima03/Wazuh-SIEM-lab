# Wazuh-SIEM-lab
A home lab created using Wazuh as SIEM and XDR platform to simulate, detect and investigate real life attack scenarios. This project covers custom detection rule development, alert triage and incident response documentation mapped to the MITRE ATT&CK framework.

**Tools and techniques used:**
 - Wazuh 4.12
 - Virtualbox
 - MITRE ATT&CK framework

**Architecture:**
This project consists of 2 virtual machines, an Ubuntu vm used as the Wazuh manager that receives logs from the Windows Wazuh agent and a Kali linux vm that attacks the Windows device to simulate real life attacks. The devices are connected through a host-only network configuration. 

![Architecture diagram](/images/github.drawio.png)


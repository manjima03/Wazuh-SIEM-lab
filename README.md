# Wazuh-SIEM-lab
A home lab created using Wazuh as SIEM and XDR platform to simulate, detect and investigate real life attack scenarios. This project covers custom detection rule development, alert triage and incident response documentation mapped to the MITRE ATT&CK framework.

**Tools and techniques used:**
 - Wazuh 4.12
 - Virtualbox
 - MITRE ATT&CK framework

**Architecture:**
This project consists of 2 virtual machines, an Ubuntu vm used as the Wazuh manager that receives logs from the Windows Wazuh agent and a Kali linux vm that attacks the Windows device to simulate real life attacks. The devices are connected through a host-only network configuration. 

![Architecture diagram](/images/github.drawio.png)

**Objectives:**
 - Deploy and configure a functional SIEM/XDR environment using Wazuh.
 - Simulate realistic attack techniques in a controlled lab environment.
 - Develop and tune custom Wazuh detection rules.
 - Monitor endpoint activity and analyze generated security alerts.
 - Investigate incidents using Wazuh dashboards and event logs.   
 - Map detected activities to the MITRE ATT&CK framework.

**Screenshots:**
![Dashboard](/images/dashboard.png)

![FIM Dashboard](/images/FIM _dashboard.png)

![failed Login](/images/Failed_login_attempt.png)

![Service creation](/images/Service_creation.png)



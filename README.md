# Azure-Logs

This project involved deploying a Windows VM honeypot in Microsoft Azure to analyze attacker behavior. The virtual network, and Network Security Group rules were configured to allow all traffic while keeping the network isolated. To make the system more attractive to attackers, the Windows Firewall was disabled.
Initial log analysis in the VM’s Event Viewer revealed numerous failed login attempts. To gain deeper insights, logs were ingested into Microsoft Sentinel. A database containing IP address ranges and their corresponding countries was then uploaded, enabling visualization of the geographic distribution of attacker IPs.


![CloudSandbox](CloudProject.png)

## Tools Utilized
Microsoft Azure
Windows VM Event Viewer

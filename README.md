# Active Directory Lab

## Objective

To create a virtualized lab environment that allows exploration of a Windows domain environment, simulates real-world cyberattacks, and enables detection of those attacks using a SIEM (Splunk). This project demonstrates skills in Active Directory management, SIEM configuration, and threat detection using simulated telemetry.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application
- SIEM (Splunk) setup, log ingestion, and query management
- Attack simulation with Atomic Red Team
- Network security monitoring and alert configuration
- cripting and automation for event logging

### Tools Used

- Virtualization: VirtualBox
- Operating Systems: Windows 10, Windows Server 2022, Ubuntu, Kali Linux
- SIEM: Splunk
- Attack Simulation: Atomic Red Team
- Other: PowerShell for automation, Windows Event Log forwarding

## Steps
1. Environment Setup: Set up and configure virtual machines for Active Directory, Splunk, and Kali Linux. Configure network settings to ensure VM communication.
   
2. Active Directory Configuration: Install Active Directory on Windows Server, set up domain users and groups, and apply security policies through Group Policy Objects.
   
3. Splunk Setup: Install and configure Splunk to ingest and parse logs from the AD server. Create indexes and set up dashboards for monitoring.
  
4. Attack Simulation: Use Kali Linux and Atomic Red Team to execute various attack techniques in the domain environment, simulating real-world adversary tactics.
   
5. Log Analysis and Detection: Review and analyze telemetry generated from attack simulations within Splunk, using queries to identify patterns of suspicious activity.
   
6. Alerting and Reporting: Set up alerts in Splunk for key indicators of compromise and export reports to summarize findings and showcase detection capabilities.

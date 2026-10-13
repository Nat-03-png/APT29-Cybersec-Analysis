# MITRE ATT&CK mapping 

 # ATT&CK                        Technique                     ID                              Description 

 initial access      |   spear phishing attachment     | T1566.001 |         Malicious email attachments used to gain access

 execution           |   PowerShell                    | T1059.001 |         Commands executed through PowerShell. Such as “computer- 
                                                                             getinfo"
 
 persistance         |   scheduled task/job            | T1053.005 |         Scheduled tasks used to maintain access.

 credential access.  |   OS credential dumping         | T1003     |         Extraction of account credentials

 command and control |   application layer protocol    | T1071     |         Communication with attacker-controlled servers. 


APT29 has been observed using PowerShell to execute commands and scripts on compromised systems. PowerShell can be used for system discovery, process enumeration, and automated task execution.

# SUMMARY
APT29 commonly uses phishing for initial access, PowerShell for execution, scheduled tasks for persistence, credential dumping for credential access, and encrypted network communications for command and control. 


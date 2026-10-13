# APT29 Attack Chain

## 1. Initial Access

APT29 has been observed using spearphishing emails to gain access to victim environments.

Example:
- Malicious email attachment
- Malicious link in an email

MITRE ATT&CK:
- T1566.001 Spearphishing Attachment
- T1566.002 Spearphishing Link

---

## 2. Execution

After gaining access, attackers may execute commands and scripts using PowerShell.

Examples:
- Get-Process
- Get-ComputerInfo
- Get-LocalUser

MITRE ATT&CK:
- T1059.001 PowerShell

---

## 3. Persistence

To maintain long-term access, attackers may create scheduled tasks or other mechanisms that automatically run when the system starts.

MITRE ATT&CK:
- T1053.005 Scheduled Task

---

## 4. Credential Access

Attackers attempt to obtain usernames, passwords, or authentication information.

Examples:
- Credential dumping
- Password extraction

MITRE ATT&CK:
- T1003 OS Credential Dumping

---

## 5. Command and Control

Compromised systems communicate with attacker-controlled infrastructure to receive instructions and send data.

MITRE ATT&CK:
- T1071 Application Layer Protocol

---

## 6. Objectives

Once access has been established, attackers may:
- Collect sensitive information
- Steal documents
- Maintain long-term access
- Conduct espionage activities



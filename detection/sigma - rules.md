title: Suspicious PowerShell Execution
id: apt29-powershell-detection
status: experimental
description: Detects potentially suspicious PowerShell activity commonly associated with attacker execution techniques.
author: Natnael Ermias
date: 2026-10-09

logsource:
  product: windows
  category: process_creation

detection:
  selection:
    Image|endswith:
      - '\powershell.exe'

  condition: selection

level: medium

# Detection Explanation

This Sigma rule detects PowerShell process execution on Windows systems.

Why it matters:
- PowerShell is a legitimate administration tool.
- Threat actors frequently abuse PowerShell for command execution and automation.
- APT29 has been observed using PowerShell during operations.

MITRE ATT&CK:
- T1059.001 PowerShell


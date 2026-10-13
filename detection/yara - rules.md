rule powershell_usage
{
   strings:
       $ps = "powershell"

   condition: 
        $ps
}

# explanation
this YARA-rule uses text based pattern matching to search for "PowerShell"

This matters because:
- power shell is a legitimate windows tool so it can blend in with normal traffic and potential adversaries do not need to bring their own/extra tools.
- adversaries may use PowerShell to execute commands and scripts
- the rule demonstrates the basics of pattern matching with YARA

![[mitre-attack-vs-cyber-kill-chain.png]]


In general terms, both systems follow the same pattern – get in, don’t get caught, steal stuff. The primary difference between the two is that the ATT&CK matrix is more a list of techniques by tactics, and doesn’t propose a specific order of operations.

The Cyber Kill Chain, is a well-defined sequence of events: The Red Team (the pentesting term for attackers) move from reconnaissance to intrusion and so on in that order. Conversely, the Red Team uses ATT&CK techniques from different tactics at different times of the scenario depending on the situation. An ATT&CK scenario could start with a Hardware Additionfrom the Initial Access tactic, then jump to Bypass User Account Control from the Privilege Escalation tactic and go back to the Execution tactic to run PowerShell.

---
description: |
  Bruteforce Kerberos to enumerate users in the domain.

  Command Reference:

    Domain Controller: A Active Directory domain controller

    Domain: The domain to use
    
    Wordlist: The wordlist of usernames to use

command: |
  kerbrute userenum --dc <DOMAIN_CONTROLLER> -d <DOMAIN> <WORDLIST>
items:
  - Shell
target: |
  - Windows_target
OS:
  - Windows
  - Linux
  - MacOS
environment: |
  - Local
  - Network
command_types:
  - Host_Enumeration
  - Privilege_Escalation
references:
  - https://github.com/ropnop/kerbrute
  - https://github.com/Cryilllic/Active-Directory-Wordlists
---

---
description: |
  Aggressive Nmap scan of all ports on a host, with verbose output.

  Command Reference:

    Target: The target to scan

command: |
  sudo nmap -v -A -p- <target>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Networking
  
command_types:
  - Information_Gathering
  - Host_Enumeration
  
references:

---

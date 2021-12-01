---
description: |
  Finds all files with the SUID bit set. To be used for privesc.

  Command Reference:

    Perm: -u=s searches for the SUID bit being set

    dev null: 2>/dev/null forwards all errors into nothingness

command: |
  find / -perm -u=s 2>/dev/null
items:

target: |
  - Linux_target
  - MacOS_target
OS:
  - Linux
  - MacOS
environment: |
  - Local

command_types:
  - Information_Gathering
  - Host_Enumeration
  - Privilege_Escalation
  
references:
  - https://www.linux.com/training-tutorials/what-suid-and-how-set-suid-linuxunix/
  - https://gtfobins.github.io/
---

---
description: |
  Show export list of nfs

  Command Reference:

    Target: Target IP to show export list of

command: |
  showmount -e <target>
  
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

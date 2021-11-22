---
description: |
  httprint fingerprinting

  Command Reference:

    Target_: The target to fingerprint

command: |
  httprint -P0 -h <target> -s /usr/share/httprint/signatures.txt
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Web
  
command_types:
  - Information_Gathering
  
references:

---

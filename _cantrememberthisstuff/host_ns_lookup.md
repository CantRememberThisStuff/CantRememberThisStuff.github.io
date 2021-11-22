---
description: |
  Identify DNS name of a target through name server

  Command Reference:

    Target: Target to lookup

command: |
  host -t ns <target>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  
environment: |
  - Networking
  
command_types:
  - Information_Gathering
  
references:

---

---
description: |
  Request zone transfer from domain to name server

  Command Reference:

    Target: Target

    Target nameserver: Target name server

command: |
  host -l <target> <target_nameserver>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  
environment: |
  - Network
  
command_types:
  - Information_Gathering
  
references:

---

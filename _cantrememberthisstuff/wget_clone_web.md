---
description: |
  Clone a website recursively using wget

  Command Reference:

    Target_url: The target url to clone recursively

command: |
  wget -mkEpnp <target_url>
  
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
  - Exploitation
  
references:

---

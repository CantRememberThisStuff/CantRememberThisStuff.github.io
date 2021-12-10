---
description: |
  Dirb directory busting using credentials

  Command Reference:

    Target_url: The target url to connect to
    
    User: Username

    Password: Password

command: |
  dirb <target_url> -u <user>:<password>
  
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
  - Host_Enumeration
  
references:

---

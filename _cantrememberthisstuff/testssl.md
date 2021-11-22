---
description: |
  Testssl to check SSL certificate info/vulns of a webdomain

  Command Reference:

    Target_url: The target url to connect to

command: |
  testssl <target_url>
  
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

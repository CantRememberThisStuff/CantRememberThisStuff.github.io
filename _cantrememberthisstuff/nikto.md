---
description: |
  Nikto without prompting for user input

  Command Reference:

    Target_url: The target url to connect to

command: |
  nikto -ask=no -h <target_url>
  
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

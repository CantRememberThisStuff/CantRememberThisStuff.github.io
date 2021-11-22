---
description: |
  Basic cURL command

  Command Reference:

    v: Verbose output, showing headers for example

    L: Follow redirects

    k: Do not perform certificate checks

    X: Set HTTP verb to use

    VERB: The HTTP verb to use

    Target: The target to connect to

command: |
  curl -vLk -X <VERB> <target>
  
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
  - Admin
  - Information_Gathering
  
references:

---

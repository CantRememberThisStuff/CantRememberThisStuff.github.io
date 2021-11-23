---
description: |
  Decode something from base64.

  Command Reference:

    String: The string to encode

command: |
  echo "<string>" | base64 -d
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Local
  
command_types:
  - Admin
  
references:
  - https://gchq.github.io/CyberChef/
---

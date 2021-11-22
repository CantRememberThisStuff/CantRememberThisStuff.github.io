---
description: |
  List modules for a specific type. Types can be: payloads, encoders, nops, platforms, archs, encrypt, formats, all.

  Command Reference:

    Type: The type to list. Can be: payloads, encoders, nops, platforms, archs, encrypt, formats, all.

    Something: Can be something to filter the output to relevant data, such as "linux", "x64", "reverse", etc

command: |
  msfvenom -l <type> | grep <something>
  
items:
  - Shell
  
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
  - Exploitation
  
references:

---

---
description: |
  Disassemble a binary.

  Command Reference:

    Binary: The binary to disassemble

command: |
  objdump -d <binary>
  
items:
  - Binary
target: |
  - Linux_target
  - MacOS_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Local
  
command_types:
  - Admin
  - Buffer_Overflow
  - Reverse_Engineering
  
references:
  - https://gchq.github.io/CyberChef/
---

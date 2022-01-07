---
description: |
  Mona is used in immunity debugger. This command finds the msp and is usefull after you crashed the application

  Command Reference:

    Buffer Size: The size of the buffer you send

command: |
  !mona findmsp -distance <buffer_size>
items:
  - Shell
target: |
  - Windows_target
OS:
  - Windows
environment: |
  - Local
command_types:
  - Admin
  - Buffer_Overflow
references:
  - https://github.com/corelan/mona
  - https://github.com/Tib3rius/Pentest-Cheatsheets/blob/master/exploits/buffer-overflows.rst
---

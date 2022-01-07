---
description: |
  Mona is used in immunity debugger. This command helps to find the badchars

  Command Reference:


command: |
  !mona bytearray -b "\x00"
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

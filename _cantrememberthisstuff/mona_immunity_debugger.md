---
description: |
  Mona is used in immunity debugger. This command sets the working directory to be used by Mona

  Command Reference:


command: |
  !mona config -set workingfolder c:\mona\%p
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
---

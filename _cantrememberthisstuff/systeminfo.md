---
description: |
  List OS information on a windows system

  Command Reference:


command: |
  systeminfo | findstr /B /C: "OS Name"/C: "OS Version"
items:

target: |
  - Windows_target
OS:
  - Windows
environment: |
  - Local
command_types:
  - Admin
  - Information_Gathering
references:

---

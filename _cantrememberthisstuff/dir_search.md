---
description: |
  Lists contents of directories (recursively) that match the provided filename.

  Command Reference:

  	File: File to look for

command: |
  dir /s /b <file>
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
  - Host_Enumeration
  - Privilege_Escalation
references:

---

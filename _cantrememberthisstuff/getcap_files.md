---
description: |
  Gets the capabilities for all files it has permission to. Can be filtered with a "grep setuid" if needed, since this would probably be most interesting.

  Command Reference:

    dev null: 2>/dev/null forwards all errors into nothingness

command: |
  getcap -r / 2>/dev/null
items:

target: |
  - Linux_target
  - MacOS_target
OS:
  - Linux
  - MacOS
environment: |
  - Local

command_types:
  - Information_Gathering
  - Host_Enumeration
  - Privilege_Escalation
  
references:
  - https://www.commandlinux.com/man-page/man8/getcap.8.html
  - https://gtfobins.github.io/
---

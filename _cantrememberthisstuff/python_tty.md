---
description: |
  Get pretty shell from shell without tty, if python is available

  Command Reference:

command: |
  python -c 'import pty; pty.spawn("/bin/sh")'
  
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
  - Exploitation
  
references:

---

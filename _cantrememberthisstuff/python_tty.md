---
description: |
  Get pretty shell from shell without tty, if python is available. Use the following to get a proper shell:
  ```
  python -c 'import pty; pty.spawn("/bin/sh")'
  <Ctrl+Z> # Background current job
  <Enter>
  stty raw -echo # This is on your localhost
  fg # Back to foreground
  <Enter>
  export TERM=xterm
  ```

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

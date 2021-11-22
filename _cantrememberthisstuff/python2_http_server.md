---
description: |
  Simple HTTP server with python command. Useful to host reverse shell files or other useful things.

  Command Reference:

    Port: The port to listen on

command: |
  python2 -m SimpleHTTPServer <port>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  - Windows
  
environment: |
  - Local
  - Web
  
command_types:
  - Admin
  
references:

---

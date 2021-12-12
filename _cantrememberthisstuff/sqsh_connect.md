---
description: |
  Connect to MsSQL database.

  Command Reference:

    Server: Server to connect to

    Username: Username to authenticate with

    Password: Password to authenticate with

command: |
  sqsh -S <server> -U <username> -P <password>
  
items:

target: |
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Networking
  
command_types:
  - Information_Gathering
  - Host_Enumeration
  
references:

---

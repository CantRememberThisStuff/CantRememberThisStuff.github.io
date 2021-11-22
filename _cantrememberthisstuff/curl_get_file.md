---
description: |
  cURL get file from url and output into file

  Command Reference:

    Target URL: The target URL to connect to

    File: File to write the output into

command: |
  curl <target_url> -o <file>
  
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
  - Web
  - Local
  
command_types:
  - Admin
  
references:

---

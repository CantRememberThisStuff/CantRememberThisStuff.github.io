---
description: |
  Output csv file on command line, using "," as separator

  Command Reference:

  	File: CSV file to read

command: |
  column -s, -t < <file> | less -#2 -N -S
items:

target: |

OS:
  - Linux
  - MacOS
environment: |
  - Local
command_types:
  - Admin
references:

---

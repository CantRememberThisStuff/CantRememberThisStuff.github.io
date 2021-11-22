---
description: |
  Remove colour from piped cli tool output

  Command Reference:

  	Command with output: Command that has coloured output

command: |
  <command with output> | sed 's/\x1B\[[0-9;]\{1,\}[A-Za-z]//g'
items:

target: |

OS:
  - Linux
environment: |
  - Local
command_types:
  - Admin
references:

---

---
description: |
  Remove colour from piped cli tool output

  Command Reference:

  	Command with output: Command that has coloured output

command: |
  <command with output> | sed -E "s/"$'\E'"\[([0-9]{1,3}((;[0-9]{1,3})*)?)?[m|K]//g"
items:

target: |

OS:
  - MacOS
environment: |
  - Local
command_types:
  - Admin
references:

---

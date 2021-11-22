---
description: |
  Connect to remote MySQL DB and dump its contents

  Command Reference:

   Username: Username to use to login

command: |
  mydumper -u <username> -a
items:
  - Username
  - Password
target: |
  - Linux_target
  - MacOS_target
  - Windows_target
OS:
  - Linux
environment: |
  - Networking
command_types:
  - Admin
  - Exploitation
references:

---

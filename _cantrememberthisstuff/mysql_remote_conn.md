---
description: |
  Connect to remote MySQL DB

  Command Reference:

    Target_host: Host to connect to

    Username: Username to use to login

command: |
  mysql -h <target_host> -u <username> -p
items:
  - Username
  - Password
target: |
  - Linux_target
  - MacOS_target
  - Windows_target
OS:
  - Linux
  - MacOS
environment: |
  - Network
command_types:
  - Admin
references:

---

---
description: |
  Greps the contents of all log files and checks them for attempts to exploit log4j (log4shell). It is also possible to check for log4j packages:
  ```
  ps aux | egrep '[l]og4j'
  find / -iname "log4j*"
  lsof | grep log4j
  ```

  Command Reference:


command: |
  egrep -i -r '\$\{jndi:(ldap[s]?|rmi)://[^\n]+' /var/log
items:

target: |
  - Linux
  - MacOS
OS:
  - Linux
  - MacOS
environment: |
  - Local
  - Web
  - Networking
command_types:
  - Admin
references:

---

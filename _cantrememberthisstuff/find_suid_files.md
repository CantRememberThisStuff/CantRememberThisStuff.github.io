---
description: |
  Greps a lot of stuff in a single regex command. You can see why I could not remember this one, right? Used to grep interesting info from web pages, for example with cURL. Greps Passwords, Usernames and more interesting things.

  Command Reference:

    Perm: -u=s searches for the SUID bit being set

    dev null: 2>/dev/null forwards all errors into nothingness

command: |
  find / -perm -u=s 2>/dev/null
items:

target: |
  - Linux_target
  - MacOS_target
OS:
  - Linux
  - MacOS
environment: |
  - Local

command_types:
  - Information_Gathering
  - Host_Enumeration
  - Privilege_Escalation
  
references:
  - https://www.linux.com/training-tutorials/what-suid-and-how-set-suid-linuxunix/
  - https://gtfobins.github.io/
---

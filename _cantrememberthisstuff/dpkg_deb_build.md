---
description: |
  Create a .deb package. This needs to have a pretty specific directory structure, so best to have a look at an existing, extracted package (commands can also be found on this site).

  Command Reference:

    Target Directory: Directory to package

command: |
  dpkg-deb --build <target_dir>

items:

target: |
  - Linux_target
OS:
  - Linux
environment: |
  - Local
  - Web
  - Networking
command_types:
  - Admin
  - Information_Gathering
  - Exploitation

references:

---

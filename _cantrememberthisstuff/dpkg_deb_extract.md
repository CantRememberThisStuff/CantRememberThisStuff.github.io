---
description: |
  Extract a .deb package to investigate (or modify...)

  Command Reference:

    Package: Package to extract

    Target Directory: Directory to extract to

command: |
  dpkg-deb --extract <package>.deb <target_directory> && dpkg-deb --control <package>.deb <target_directory>/DEBIAN

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

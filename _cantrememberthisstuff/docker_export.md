---
description: |
  Export container for use on other machines.

  Command Reference:

    Name: Name to give to container export

    Image Tag: Image to use


command: |
  docker export <image_tag> | gzip > <name>.gz
  
items:

target: |
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Local
  - Docker

command_types:
  - Admin
  
references:
  - https://www.infosecmatter.com/install-nessus-in-docker/
---

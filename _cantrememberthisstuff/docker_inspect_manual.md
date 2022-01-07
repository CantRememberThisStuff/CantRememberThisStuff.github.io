---
description: |
  Save container to tarball, unpack it and inspect manifest.json to know what should be inspected next.

  Command Reference:

    Output: Output tarball

    Image: Image to use


command: |
  docker save -o <output>.tar <image> && tar -xvf <output>.tar && cd <output> && cat manifest.json | jq
  
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
  - Information_Gathering
  - Host_Enumeration
  
references:
---

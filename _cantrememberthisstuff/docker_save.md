---
description: |
  Save container to tarball.

  Command Reference:

    Output: Output tarball

    Image: Image to use


command: |
  docker save -o <output>.tar <image>
  
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
---

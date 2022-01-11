---
description: |
  Build and upload a project to PyPi.

  Command Reference:


command: |
  python3 -m build && python3 -m twine upload --repository pypi dist/*
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  - Windows
  
environment: |
  - Local
  - Web
  
command_types:
  - Admin
  
references:

---

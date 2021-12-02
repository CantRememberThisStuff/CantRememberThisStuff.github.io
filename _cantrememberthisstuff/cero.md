---
description: |
  Use cero to find domains from certificates provided during TLS handshake

  Command Reference:

    Domain: The domain to connect to

    TLD: Top level domain

command: |
  cero <domain>.<tld>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target

services:
  - HTTPS
  - SMTPS

OS:
  - Linux
  - MacOS
  
environment: |
  - Web
  
command_types:
  - Admin
  - Information_Gathering
  
references:
  - https://github.com/glebarez/cero
  
---

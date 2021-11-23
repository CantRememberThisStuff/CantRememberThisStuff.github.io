---
description: |
  Figure out Virtual Hosts using ffuf. By using the "Host" header you can bruteforce subdomains that the server might be listening on.

  Command Reference:

    Target_url or IP: The target url or IP to connect to
    
    Wordlist: Wordlist to use for directory busting
    
    Domain: The main domain the 

command: |
  ffuf -w <wordlist> -H "Host: FUZZ.domain.tld" -u https://<target_url_or_ip>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Web
  
command_types:
  - Information_Gathering
  - Host_Enumeration
  
references:
  - https://github.com/ffuf/ffuf
---

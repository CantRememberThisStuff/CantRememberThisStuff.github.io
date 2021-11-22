---
description: |
  Gobuster, using a large number of extensions. Outputs information into a file as full urls.

  Command Reference:

    Target_url: The target url to connect to
    
    Wordlist: Wordlist to use for directory busting
    
    Output file: File to write results into

command: |
  gobuster -x php,html,txt,md,sh,exe,py,tgz,bak -w <wordlist> -eu <target_url> -o <output_file>
  
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

---

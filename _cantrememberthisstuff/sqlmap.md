---
description: |
  SQLmap running automated, not requireing user input, while detecting user input forms.

  Command Reference:

    Target_url: The target url to connect to
    
    Wordlist: Wordlist to use for directory busting
    
    Output file: File to write results into

command: |
  sqlmap --forms --batch --crawl=10 -u <target_url>
  
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
  - Host_Enumeration
  - Exploitation
  
references:

---

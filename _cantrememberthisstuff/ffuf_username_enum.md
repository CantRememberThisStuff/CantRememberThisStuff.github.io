---
description: |
  Example username enumeration with ffuf.

  Command Reference:

    Target_url: The target url to fuzz on
    
    Wordlist: Wordlist to use for directory busting
    
	w: wordlist parameter
	
	u: url parameter
	
	H: Custom header
	
	X: HTTP method
	
	mr: Text on page, indicating username is valid.
	
	d: Data to send with the post request
	
	FUZZ: The content to fuzz

command: |
  ffuf -w <wordlist> -X POST -d "username=FUZZ&email=x&password=x&cpassword=x" -H "Content-Type: application/x-www-form-urlencoded" -u <target_url>/customers/signup -mr "username already exists"

  
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

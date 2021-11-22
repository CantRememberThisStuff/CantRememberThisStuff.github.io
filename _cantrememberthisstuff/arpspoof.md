---
description: |
  Use arpspoof (Adress Resolution Protocol) to intercept traffic from and to a certain host. This requires IP forwarding, turning the attack machine into a router.

  Command Reference:

    Target: The target

    Host: Pretend to be this host

    Interface: The Interface to listen on

command: |
  echo 1 > /proc/sys/net/ipv4/ip_forward
  arpspoof -i <interface> -t <target> -r <host>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  
environment: |
  - Network
  
command_types:
  - Information_Gathering
  - Host_Enumeration
  
references:

---

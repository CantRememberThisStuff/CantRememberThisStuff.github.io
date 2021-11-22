---
description: |
  Tcpdump to listen to all traffic on all interfaces and write into a .pcap file. Filtering is easier to do in Wireshark and better to have all the traffic than not having enough.

  Command Reference:

    File: File to write into (.pcap)

command: |
  tcpdump -w <file>
  
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
  
references:

---

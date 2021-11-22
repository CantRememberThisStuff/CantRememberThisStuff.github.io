---
description: |
  SSH port forwarding, for example for a port of a host in a remote network, where you have access to another host. This can for example allow you to view webpages in a regular browser on you own machine, that would otherwise be inaccessible. Or, it allows you to RDP from your local machine, through the tunnel, to the remote host. After executing this command correctly, you will be able to connect to your localhost:localport, which will tunnel the connection straight to the targetip:targetport

  Command Reference:

    Local Port: Port of your local machine as one end of the tunnel

    Target IP: IP address of the target machine, of which you want the port to be forwarded to your local one

    Target Port: Port of the target machine that you want tunneled to yours

    User: User on the machine where you have SSH access, and that has access to the target machine

    Middle Machine IP: The IP address of the machine to which you have SSH access

command: |
  ssh -L <local_port>:<target_ip>:<target_port> <user>@<middle_machine_ip>
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  
environment: |
  - Networking
  
command_types:
  - Information_Gathering
  
references:

---

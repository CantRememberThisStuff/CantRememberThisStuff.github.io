---
description: |
  Run docker container and expose ports externally, for example to use for SSH or web servers in the docker container.

  Command Reference:

    Name: Name to give to container, for easy referencing

    Image Tag: Image to use

    Container Port: Port of container wish to expose externally

    Host Port: Port of host you wish to use to expose the container port


command: |
  docker run --name <name> -p <host_port>:<container_port> -it <image_tag>
  
items:

target: |
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Local
  - Network
  - Docker
  
command_types:
  - Admin
  
references:
  - https://www.infosecmatter.com/install-nessus-in-docker/
---

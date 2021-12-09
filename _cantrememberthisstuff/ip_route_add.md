---
description: |
  Add a route to a network in the route table

  Command Reference:

  	Network IP: IP of the network you want to reach

    CIDR: Range of the network you want to reach (24,16,etc.)

    Gateway IP: IP of the gateway between you and the network you want to reach

command: |
  ip route add <network_ip>/<cidr> via <gateway_ip>
items:

target: |

OS:
  - Linux
  - MacOS
environment: |
  - Local
  - Network
command_types:
  - Admin
references:

---

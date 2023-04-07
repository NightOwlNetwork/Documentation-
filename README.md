# Documentation
| Author        |Link           |Description  |
| ------------- |-------------| -----|
| Group Project | [Scenario](https://github.com/NightOwlNetwork/Documentation-/blob/main/scenario%20.pdf) |   Night Owl Network was tasked with updating the core IT infrastructure of a recent GlobeX acquisition called CleanPower to ensure the security and reliability of the network infrastructure |
| Siearra Maldonado   | [Cleanpower.CSV](https://github.com/NightOwlNetwork/Documentation-/blob/main/Cleanpower.csv)     | CSV document with the employee information that is being used by a script to autopopulate the user's Active Directory profile. |
| Siearra Maldonado  | [Cleanpower.xlsx](https://github.com/NightOwlNetwork/Documentation-/blob/main/Cleanpower.xlsx)     | Excel document with the employee information |
| Night Owl Network Team    | [Powerpoint.pdf](https://github.com/NightOwlNetwork/Documentation-/blob/main/Project%202.pdf)  | PDF format of the Powerpoint presentation  |
| Geneva Knott | [Topology Before](https://github.com/NightOwlNetwork/Documentation-/blob/main/Topology%20Before.pdf)      |Physical topology before implementation |
| Geneva Knott  | [ Network Topology VPN Tunnel](https://github.com/NightOwlNetwork/Documentation-/blob/main/Topology%20After.png)      | Physical topology with implementated software  |
| Nick Alderete | [Network Infastructure Data](https://github.com/NightOwlNetwork/Documentation-/blob/main/Network%20Chart.png)     | Table displaying the network information    |

## Topology before
![before](https://github.com/NightOwlNetwork/Documentation-/blob/main/topologybefore.png)
CleanPower was working on a basic hierarchical network infrastructure. At the center of the diagram is the core router, which is the central point of connectivity for all devices on the network. The router is allowing for internet access to any end-user devices, such as computers and printers. The router is using Pfsense as their firewall. Behind the Pfsense is the server which provides centralized management and storage for the network's resources. Overall, this topology appears to be a basic hierarchical network design, with a router providing scalability and redundancy with minimal security and minimal control of user privilege.



## Final Topology
![After OpenVpn/CaptivePortal/FreeRADIUS](https://github.com/NightOwlNetwork/Documentation-/blob/main/Topology%20After.png)
Overall, the changes made by Night Owl Network topology are aimed at increasing scalability, redundancy, and security, while also adding support for wireless devices. The network topology diagram was designed for an OpenVPN connection between two sites using pfSense firewalls. The network consist of two sites: Site 1 and site 2. Each site has it's own network with several devices connected to it. the routers are using pfsense firewall depicted by the blue router on the topology. The router is responsible for connecting the LAN network to the internet. The two sites are connected via an OpenVPN tunnel, which is represented by the tunnel connecting the two pfSense firewalls. This tunnel provides a secure and encrypted connection between the two sites, allowing users at each site to access resources on the other site's LAN network. The network used by CleanPower has been updated to connect two sites over the internet using OpenVPN and pfSense firewalls.


## 
![Chart](https://github.com/NightOwlNetwork/Documentation-/blob/main/Network%20Chart.png)

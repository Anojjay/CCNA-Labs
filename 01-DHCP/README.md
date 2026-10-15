# DHCP Server & DHCP Relay Lab

Configured R2 as a DHCP server with three DHCP pools for different subnets, including excluded IP addresses, DNS settings, and default gateways. Configured R1's G0/0 interface as a DHCP client and G0/1 as a DHCP relay agent using `ip helper-address`.

Tested DHCP address assignment on client PCs using `ipconfig /renew` and verified network settings using `ipconfig /all`.

**Key Concepts:** DHCP pools, DHCP relay, excluded addresses, DHCP clients, IP address assignment.

**Tools:** Cisco Packet Tracer, Cisco IOS CLI

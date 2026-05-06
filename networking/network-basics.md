IP addressing
An IP address identifies a device on a network.
Example format is 192.168.1.10.
Each device must have a unique address.

Subnet
A subnet splits a network into smaller sections.
Devices must be in the same subnet to communicate directly.
Example
PLC 192.168.1.10
HMI 192.168.1.20
Subnet 255.255.255.0

Default gateway
The gateway connects one network to another.
It is used when devices need to communicate outside their subnet.

Switching
A network switch connects devices in a local network.
It forwards traffic based on MAC address.
In a panel, PLC, HMI, and drives connect through a switch.

VLAN
A VLAN separates networks logically on the same hardware.
Used to isolate systems.
Example
Separate PLC network from office network.

OT example
A basic control network may include
PLC
HMI
Drives
Engineering laptop

All devices communicate over Ethernet using IP addressing.

Security note
Flat networks increase risk.
Segmentation using VLANs or firewalls improves security.

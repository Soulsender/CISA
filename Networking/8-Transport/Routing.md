- MTU (maximum transmission unit)
- hosts can send to 
	- loopback
	- local
	- remote
#### Fragmenting
- fragmentation is when layer 3 splits IPv4 packet into smaller units
- causes latency
- IPv6 does not fragment packets
- ex. when router goes from ethernet to a slow WAN with a smaller MTU

#### Static Routing
- is safe
- `192.168.10.0 255.255.255.0 209.165.200.225` static route
- `192.168.10.0 255.255.255.0 G0/0/1` static route
- `ip route 0.0.0.0 0.0.0.0 S0/0/0` static default route (for internet)


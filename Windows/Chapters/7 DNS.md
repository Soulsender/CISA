#### Zones
- primary - read/write copy of dns database
- secondary - read only copy of dns database
- stub
	- copy of a zone that contains only records used to locate name servers
	- improves performance
	- used when the domain name is below a higher level
- zone replication
	- AD integrated zones
		- perform incremental replication
		- adjust AD replication schedule
	- traditional dns zones
		- replicate between primar/secondary zones
		- perform an incremental rather than a complete zone transfer

#### Forwarding
- server used to resolve external dns (ie. google.com)
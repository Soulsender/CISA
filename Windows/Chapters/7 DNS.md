#### Zones
- primary - read/write copy of dns database
- secondary - read only copy of dns database
- stub
	- copy of a zone that contains only records used to locate name servers
	- improves performance
	- used when the domain name is below a higher level
	- does not have authority
- zone replication
	- AD integrated zones
		- perform incremental replication
		- adjust AD replication schedule
	- traditional dns zones
		- replicate between primar/secondary zones
		- perform an incremental rather than a complete zone transfer
#### Forwarding
- server used to resolve external dns (ie. google.com)
#### DNS Security
- cache locking
	- prevents entries from being overwritten until a TTL has passed
- socket pool
	- randomizes source port for issuing DNS queries
- DANE
	- uses TLSA records that state the CA where they should expect a cert
- DNSSEC
	- enables signing DNS records
- RRL
	- ignores DDOS queries
- unknown record support
	- will not do any record-specific processing for unknown records

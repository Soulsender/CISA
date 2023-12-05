- DNS zones are used any time a domain name wishes to have DNS records
#### Forward Lookup Zones
- converts a name to an IP address or another name
- starts with a name
- used when you want to have a name instead of an IP address
#### Reverse Lookup Zones
- contains all the records of IP addresses to their domain names
- converts an IP address to a name
- should be implemented as often as possible
- can aid in troubleshooting
- basically hold a copy of the primary zone
#### Primary Zone
- main zone
- read/write copy of data
- all changes are made here then replicated to secondary zones
#### Secondary Zone
- read-only copy of primary zone
- can only retrieve updates, not process them
- cannot be AD integrated
- reduces workload on primary zone
#### Stub Zones
- redirects to an authoritative dns server
- partial zone data
- only contain SOA, NS, and A records
#### Zone Transfers
- take place when they are not integrated with AD
- master DNS servers transfer zone data from master to secondary
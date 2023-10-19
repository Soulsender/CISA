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
#### Stub Zones
- redirects to an authoritative dns server
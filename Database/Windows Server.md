#### Datacenter
- large servers
- supports up to 64 CPUs
- fault tolerance - hot-add processors
- only available to purchase through MSDN (microsoft volume-licensing programs) or OEMs (original equipment manufacturer)

#### Standard
- full set of Windows server features
- only differs from Datacenter by number of virtual machine instances allowed

#### Essentials
- includes all Datacenter features except
	- Server Core
	- Hyper V
	- Active Directory Federation Services
- Limited to one physical or virtual server instance
- Maximum of 25 users

#### Foundation
- reduced version
- supports only basic features:
	- Active Directory domain services
	- Active Directory rights management services
	- File and print services
	- Application support
- No virtualisation rights
- Limited to 15 users

## Supporting Server Roles
Basic categories of Servers

#### Directory Services
- store
- organise
- supply info about a network and its resources
- AD certificate services
	- public key certification
- AD domain services
	- domain controller
- AD federation services
	- single sign-on
- AD lightweight directory services
	- directory-enable application

#### Infrastructure Services
- provide support services for network clients
- DHCP
- DNS server
- Hyper V
- Remote access
- VPN
- IP routing
- NAT
- Volume activation services
	- key management system (KMS)
- Windows deployment services (WDS)
	- install windows OS remotely
- Windows server update services (WSUS)
	- windows updates

#### Application Services
- provide communication services
- operating environment
- programming interfaces for specific applications
- fax server
- print and file storage
#### Active directory domain services (AD DS)
- stores information about domain members, devices, users 
- verifies credentials
- defines access rights
- server running this is a DC

#### Group Policy
- controls enviroment
- set of group policies is a group policy object (GPO)
- version of group policy is local group policy (LGPO)
	- used when AD is not being used
- dissiminate group policies by listing them in their LDAP dir

#### KCC
- generates replication topology
- generates map of connections between DCs in the forest
- dynamic adjustments
	- changes based on the network
- decides which DCs replicate with other DCs and how often
- default runs every 15 minutes

#### Metadata Information Hierarchy
- "whenChanged" timestamp
- version numbers

#### Scope of Configuration Management
- config items (CIs) elements, components, or resources that are subject to config management
	- includes servers, routers, software, docs, configs, and more
- relationships between CIs
	- understanding and documenting relationships/dependancies between CIs
- change control
- asset management
- documenation

#### Types
all groups have universal, global, domain local, and local scopes
- security group
	- simplify user access management by allowing admins to transfer permissions
- distribution group
	- allow AD admins to create a pool of users to send messages or emails through to
	- deals with email
#### Group Scopes
- universal
	- AD users from different domains can join as members
	- two or more universal groups can be nested in the same forest by the AD admin
	- can access network resources belonging to any other domain in the forest
- global
	- includes users and other global groups from their domain
	- allows members to access resources belong to other trusting domains in the same forest
	- nesting is allowed
	- good for categorizing employees into different groups based on roles
- domain local
	- members can access resources belonging to the same domain only
- local
	- can only access resources on the local computer
	- can operate without DCs
#### Other Groups
- dynamic
	- simplifies AD group management
	- automatically adds or removes users from the group
- special identity
	- similar to security groups
	- memberships are managed automatically
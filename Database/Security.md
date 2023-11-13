#### Fixed Server Roles
- Bulkadmin - can perform bulk inserts
- DBcreator - create, alter, drop, and restore dbs
- DIskadmin - create, alter and drop disk files
- Proccessadmin - kill running SQL server process
- Securityadmin - manage logins for the server
- Serveradmin - configure server-wide settings including settting up full text searched and shutting down the server
- Setupadmin - configure linked servers, extended stored procedures, and startup stored procedure
- Sysadmin - perform any activity in the SQL server install regardless of other permissions
```sql
EXEC sp_addsrvrolemember ‘XPS\Lauren’, ‘sysadmin’
```
#### Public Server Role
- fixed role
- can have object permissions like a standard role
- users are automatically a member
- minimum permission level
#### User-Defined Roles
- used to limit server permissions to users
#### Grant DB access
```sql
USE Family CREATE USER ‘XPS\Lauren’, ‘LRN’
```
#### Fixed Database Roles
- db_accessadmin: Authorizes a user to access the database, but not to manage databaselevel security. 
- db_backupoperator: Allows a user to perform backups, checkpoints, and DBCC commands, but not restores. (Only server sysadmins can perform restores.) 
- db_datareader: Authorizes a user to read all data in the database. This role is the equivalent of a grant on all objects, and it can be overridden by a deny permission. 
- db_datawriter: Allows a user to write to all data in the database. This role is the equivalent of a grant on all objects, and it can be overridden by a deny permission. 
- db_ddladmin: Authorizes a user to issue DDL commands (create, alter, drop). 
- db_denydatareader: Permits a user to read from any table in the database. This overrides any object-level grant. 
- db_denydatawriter: Blocks a user from modifying data in any table in the database. This overrides any object-level grant. 
- db_owner: This is a special role that has all permissions in the database. This role includes all the capabilities of the other roles and differs from the dbo user role. This is not the database-level equivalent of the server sysadmin role because an object-level deny will override membership in this role. 
- db_securityadmin: Permits a user to manage database-level security—including roles and permissions. ASSIGNING FIXED DATAB
#### Assigning Fixed Database Roles
```sql
USE AdventureWorks; 
CREATE ROLE auditors AUTHORIZATION db_securityadmin; GO
```
#### Granting Object Permissions
```sql
GRANT Permission, Permission ON Object TO User/role, User/role WITH GRANT OPTION
```

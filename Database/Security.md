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
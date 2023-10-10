- data definition language (DDL)
- data manipulation language (DML)
- database management system (DBMS)
- index
- table
- XQuery
#### Constraints
- limitations or rules placed on a field
- ex. age cannot be negative number
- unique
	- guarantees values will not repeat one another
- check
	- define logical condition
	- will evaluate to t/f
- default
	- when no data is provided at insert time
	- db will automatically use the defined value
	- if not used, db will use null value
- not null
	- will not accept null values
- primary key
	- each table can only have one primary key
	- ex. BCIT uses your A123456 number
	- most unique
	- more detailed, more requirements
- foreign key
	- reference another parent table
	- basically like a pointer

#### Database Types
- flat-type database
	- two dimensional table of rows and columns
- hierarchical database
	- similar to tree structure
	- parent tables have child tables
	- only one parent for each child
- relational database
	- similar to hierarchical database
	- can have multiple parents

#### Interactions
- SQL CMD
	- command line application that allows SQL queries to be written and executed from cmd
- transact SQL
	- primary means of programming and managing SQL server
	- exposes keywords
	- SSMS is just transact SQL under the hood

#### Data Manipulation Language (DML)
- SELECT
	- retrieves rows fromdb
- INSERT
	- adds one or more rows to a table or view
- UPDATE
	- changes existing data
- DELETE
	- removes rows from table/view
- MERGE
	- performs insert, update, or delete operations on a target table

#### Data Definition Language (DDL)
- USE
	  changes database context
- CREATE
	- creates SQL server database object (table/view)
- ALTER
	- changes existing object
- DROP
	- removes an object from the db
- TRUNCATE
	- removes rows from table and frees the space removed
- DELETE
	- removes rows from table but does not free spaced removed

#### Data Manipulation Language (DML)
- **SELECT**
	- retrieves rows fromdb
```sql
SELECT * FROM tableName;
SELECT column1, column2 FROM tableName;
```
- **INSERT INTO**
	- adds one or more rows to a table or view
```sql
INSERT INTO tableName (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```
- **UPDATE**
	- changes existing data
```sql
UPDATE tableName  
SET column1 = value1, column2 = value2, ...  
WHERE condition;

UPDATE employees 
SET salary = salary * 1.1 
WHERE department = 'Marketing';
```
- **DELETE**
	- removes rows from table/view
```sql
DELETE FROM tableName WHERE condition;
```
- **MERGE**
	- performs insert, update, or delete operations on a target table
```sql
MERGE TargetProducts AS Target
USING SourceProducts AS Source
ON Source.ProductID = Target.ProductID

-- For Inserts
WHEN NOT MATCHED BY Target THEN
    INSERT (ProductID,ProductName, Price)
    VALUES (Source.ProductID,Source.ProductName, Source.Price)

-- For Updates
WHEN MATCHED THEN UPDATE SET
    Target.ProductName = Source.ProductName,
    Target.Price = Source.Price

-- For Deletes
WHEN NOT MATCHED BY Source THEN
    DELETE;
```
- **UNION**
	- combines results of two or more queries into resulting single set
#### Data Definition Language (DDL)
- **USE**
	  changes database context
```sql
USE database;
```
- **CREATE**
	- creates SQL server database object (table/view)
```sql
CREATE TABLE tableName (
	column1 datatype,
	column2 datatype
);
```
- **ALTER**
	- changes existing object
```sql
ALTER TABLE tableName
ADD columnName datatype;

ALTER TABLE tableName
DROP COLUMN columnName;
```
- **DROP**
	- removes an object from the db
```sql
DROP TABLE tableName;
```
- **TRUNCATE**
	- removes rows from table and frees the space removed
```sql
TRUNCATE TABLE tableName;
```
- **DELETE**
	- removes rows from table but does not free spaced removed
```sql
DELETE FROM tableName WHERE name='John Name';
```
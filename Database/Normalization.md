
#### First normalization form (1NF) 
- eliminate repeating groups
- no duplicate records
- must have primary key
- cannot have multivalued attributes
- entries must be same data type
#### Second normalization form (2NF) 
- eliminate redundant data
- entirely based on dependency 
- if an attribute depends on one primary key attributes but not the others, this violates 2NF
#### Third normalization form (3NF) 
- eliminate columns not dependent on key
- transitive dependencies
- when attribute1 is dependent on attribute 2 which depends on the primary key
- must not contain columns that aren't fully dependent on the primary key
- cannot be a product of something from another column (ie. something multiplied)
#### Fourth normalization form (4NF) 
- isolate independent multiple relationships
#### Fifth normalization form (5NF)
- isolate semantically related multiple relationships (wtf does this even mean)

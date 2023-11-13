#### Simple Recovery
- least administration
#### Full Recovery
- restores to a point in time
- logs can  grow in size a lot
- when backups are performed, logs must be shrunk and truncated
#### Bulk Logged
- compromise between the two
- least used
- good performance with least log space
- no point in time recovery
#### Types
- full 
	- all data
- differential 
	- based on the latest full backup of data aka base of differential
	- contains only data changed since differential base
	- smaller and faster than full
- incremental
	- based on the last backup
	- contains only data changed since last full or incremental backup
	- smaller and faster than other two
#### GPT (GUID Partition Table)
- associated with UEFI
- every partition has a globally unique identifier
- size depends on the OS
- nearly unlimited number of partitions
- windows allows up to 128 partitions
- stores multiple copies of boot data and partitioning
- stores CRC cyclic redundancy check to check for corruption

#### MBR (Master Boot Record) - legacy
- limited to disks less than 2 TB
- only supports up to 4 primary partitions
- partitioning and boot data is stored in one place, makes it risky

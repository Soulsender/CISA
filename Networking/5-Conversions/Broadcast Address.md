- `192.168.10.10/20` -> `192.168.00001010.255`
- `192.168.0000|1010.255` where `|` is /20
- add the host bits up
- `1010` -> `1111` -> 15
- `192.168.15.255` final answer
![[Broadcast Address-1696363079097.jpeg]]

- `192.168.10.10/30` -> `192.168.10.00001010`
- `192.168.10.000010|10` where `|` is /30
- add the host bits and the one network bit
- `10|10` -> `1|11` -> 11
- `192.168.10.11` final answer
### Keybindings
- Ctrl + C -> cancel current task, clear line
- Ctrl + Shift + 6 -> cancel "translating" task

#### Navigation
- `enable` enter priv EXEC (`en`)
- `disable` enter user EXEC
- `configure terminal` global mode (`conf t`)
- `end` enter from any mode to priv EXEC mode

#### Misc
- `description {description}` give item description
- `banner motd {banner}` create a warning banner
- `traceroute {ip}` traceroute ip address

#### Show (`sh`)
- `show version` get version and system info
- `show interface status` show all interfaces
- `show ip interface brief` show ip address information
- `show running-config` show current config
- `show startup-config` show boot config

#### Config (`conf`)
- `line console 0` enter **console** config interface (`line con 0`)
- `line vty 0 15` enter **virtual terminal** config interface (for SSH, Telnet)
- `interface vlan 1` enter **vlan** config interface
- `interface FastEthernet 0/1` enter ethernet config interface (`int fa 0/1`)
- `no shutdown` enable virtual interface
- `copy running-config startup-config` save running & startup config files
- `erase startup-config` erases startup-config
- `reload` restore to startup-config (device will go offline briefly)

#### Passwords
- `password {password}` change user EXEC password (used in `line console 0` and `line vty 0 15`)
- `login` enable user EXEC password access
- `enable secret {password}` change priv EXEC password
- `service password-encrypion` enable password encryption

#### IP Addressing
- `ip address {192.168.1.20} {255.255.255.0}` set a manual ip address and subnet mask
- `ip default-gateway {192.168.0.254}` set the router address
- `show ip interface brief` show ip address information
#### Navigation
`enable` enter priv EXEC
`disable` enter user EXEC
`configure terminal` global mode
`end` enter from any mode to priv EXEC mode

#### Misc
`description {description}` give item description
`banner motd {banner}` create a warning banner
`traceroute {ip}` traceroute ip address

#### Config
`line console 0` enter **console** config interface 
`line vty 0 15` enter **virtual terminal** (SSH, Telnet)
`show running-config` show current config
`show startup-config` show boot config
`copy running-config startup-config` save running & startup config files
`reload` restore to startup-config (device will go offline briefly)
`erase startup-config` erases startup-config

#### Passwords
`password {password}` change user EXEC password (used in `line console 0` and `line vty 0 15`)
`login` enable user EXEC password access
`enable secret {password}` change priv EXEC password
`service password-encrypion` enable password encryption

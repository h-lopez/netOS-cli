# netOS-cli
a keyword highlighting list for secureCRT

this keyword list highlights contextual keywords and phrases to make administration of network devices easier.

### requirements
- Secure CRT 8.5 or later

### features
highlights the following:
- interface names
- IPv4/IPv6 addresses
- MAC addresses
- contextual keywords (eg. disabled, shutdown, etc)
- protocol specific information (BGP)

### compatible/tested systems
- Cisco IOS
- Cisco IOS-XE
- Cisco IOS-XR
- Cisco NX-OS
- Linux-based systems (Debian, Fedora, RHEL, Ubuntu, etc + FRRouting)
- Juniper JunOS
- VyOS

works with other network operating systems as well, but not thoroughly tested.

### install instructions:
1. clone this repo or download `net_os_cli.ini`
1. copy `net_os_cli.ini` to your secureCRT's keyword list directory (usually located at `%appdata%\VanDyke\Config\Keywords`)
1. select the active keyword list in secureCRT (_Options > Edit Default Session > Terminal > Keyword Highlighting_)
1. under advanced (within _Keyword Highlighting_ settings), make sure highlight style has only _color_ enabled and set match style to _phrases and substrings_
1. if you need this enabled by default, make sure you select '_change ALL sessions (no undo)_' after clicking ok to save settings.

any new sessions will start with keyword highlighting enabled.

some screenshots: 

**Cisco IOS-XR**


![IOS-XR](https://i.imgur.com/LaJmjfe.png)

**Juniper Junos**

![Junos](https://i.imgur.com/cNxhFHS.png)

**VyOS**

![VyOS](https://i.imgur.com/7TwiqwU.png)

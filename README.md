# netOS-cli
keyword highlighting list for secureCRT

works with Cisco IOS-XE/XR/NX-OS and juniper Junos, along with support for linux and VyOS.
may work with other network operating systems as well
compatible with secureCRT >8.5 (may work on, but not tested with, older versions)

highlights interfaces, IPv4/v6 addresses/subnets, MAC addresses and contextual keywords. 

install instructions:
1. copy 'net_os_cli.ini' to your secureCRT's keyword list directory (usually located at _%appdata%\VanDyke\Config\Keywords_)
1. select keyword list in secureCRT (Options > Edit Default Session > Terminal > Keyword Highlighting)
1. under advanced (within Keyword Highlighting settings), make sure highlight style has only _color_ enabled and set match style to _phrases and substrings_
1. if you need this enabled by default, make sure you select '_change ALL sessions (no undo)_' after clicking ok to save settings.

any new sessions will start with keyword highlighting enabled.

some screenshots: 

Cisco IOS-XR

![IOS-XR](https://i.imgur.com/LaJmjfe.png)

Juniper Junos

![Junos](https://i.imgur.com/cNxhFHS.png)

VyOS

![VyOS](https://i.imgur.com/7TwiqwU.png)

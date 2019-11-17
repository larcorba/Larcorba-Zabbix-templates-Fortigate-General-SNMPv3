Zabbix template
======

Intro
------
Check out Zabbix share and drop a rating/comment! :)

https://share.zabbix.com/network_devices/fortigate/fortigate-snmpv3-general

There's two templates in this Git! Note that one is for a Fortigate cluster and the other is for a standalone one!

Features
------
- SNMPv3
- Interface disovery
- General health
- Inventory


Macros
------
It's important to add your authentication details in a Macro!

{$FGT_V3_USER} = Username

{$FGT_V3_AUTHPASS} = Authentication and Privacy key


Inventory
------
Make sure to add the inventory 'automatic' options at your host if you want to use the invetory option.


Zabbix template
======

Intro
------
Check out Zabbix share and drop a rating/comment! :)

https://share.zabbix.com/network_devices/fortigate/fortigate-snmpv3-general


Features
------
- SNMPv3
- Interface disovery
- General health


Macros
------
It's important to add your authentication details in a Macro!

{$FGT_V3_USER} = Username

{$FGT_V3_AUTHPASS} = Authentication and Privacy key


Inventory
------
Make sure to add the inventory 'automatic' options at your host if you want to use the invetory option.

Logical interface disovery
------
^(fe|ge|xe|et)-[0-9]+\/[0-9]+\/[0-9]+\.[0-9]+$|^(fe|ge|xe|et)-[0-9]+\/[0-9]+\/[0-9]+$|^(reth|st)[0-9]+\.[0-9]+$|^(reth|st)[0-9]$|^vcp-[0-9]+$|^vlan.[0-9]+$

or

^(fe|ge|xe|et)-[0-9]+\/[0-9]+\/[0-9]+$|^(fe|ge|xe|et)-[0-9]+\/[0-9]+\/[0-9]+$|^(reth|st)[0-9]+$|^(reth|st)[0-9]$|^vcp-[0-9]+$|^vlan.[0-9]+$

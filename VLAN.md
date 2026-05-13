# VLAN Commands

## Create VLAN
conf t
vlan 10
name ADMIN

## Assign VLAN to Port
interface f0/1
switchport mode access
switchport access vlan 10

## Configure Trunk
interface g0/1
switchport mode trunk

## Allow Specific VLANs
switchport trunk allowed vlan 10,20,30

## Show VLANs
show vlan brief

## Show Trunks
show interfaces trunk

## Delete VLAN
no vlan 10

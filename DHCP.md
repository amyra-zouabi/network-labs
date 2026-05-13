# DHCP Commands

## Exclude IP Addresses
ip dhcp excluded-address 192.168.1.1 192.168.1.10

## Create DHCP Pool
ip dhcp pool LAN

## Define Network
network 192.168.1.0 255.255.255.0

## Default Gateway
default-router 192.168.1.1

## DNS Server
dns-server 8.8.8.8

## Lease Time
lease 7

## Show DHCP Bindings
show ip dhcp binding

## Show DHCP Pool
show ip dhcp pool

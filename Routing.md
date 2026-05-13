# Routing Commands

## Configure Interface IP
interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

## Static Route
ip route 0.0.0.0 0.0.0.0 192.168.1.254

## Show Routing Table
show ip route

## Enable Routing
ip routing

## Router-on-a-Stick
interface g0/0.10
encapsulation dot1Q 10
ip address 192.168.10.1 255.255.255.0

interface g0/0.20
encapsulation dot1Q 20
ip address 192.168.20.1 255.255.255.0

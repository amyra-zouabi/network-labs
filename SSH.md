
# SSH Configuration

## Configure Hostname
hostname R1

## Configure Domain
ip domain-name company.local

## Create User
username admin secret StrongPassword

## Generate RSA Keys
crypto key generate rsa

## Enable SSH Version 2
ip ssh version 2

## Configure VTY Lines
line vty 0 4
login local
transport input ssh

## Show SSH
show ip ssh
show ssh

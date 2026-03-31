# Mac-Address-Spoofing-Project

## Description
This project shows how to change the MAC address using kali linux

## Tools Used 
- macchanger
- ifconfig

## Steps
1. sudo su
2. ifconfig
3. ifconfig eth0 down
4. macchanger -r eth0
5. ifconffig eth0 up
6. ifconfig

## Restore MAC
1. ifconfig eth0 down
2. macchanger -p eth0
3. ifconfig eth0 up

## Result 
MAC address changed successfully and restored again

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
   <img width="1819" height="808" alt="image" src="https://github.com/user-attachments/assets/1d9dc463-3619-4ed5-835b-a05afe08652d" />


## Restore MAC
1. ifconfig eth0 down
2. macchanger -p eth0
3. ifconfig eth0 up
   <img width="1920" height="902" alt="image" src="https://github.com/user-attachments/assets/36a09e46-c0bd-4051-93e6-b0ffe8b50883" />


## Result 
MAC address changed successfully and restored again







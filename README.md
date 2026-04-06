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

## Screnshts

### Before.png
<img width="1920" height="901" alt="Screenshot_2026-03-31_08-41-23" src="https://github.com/user-attachments/assets/8be83106-8d64-49c8-ad0d-12db6ee9efb6" />

### after.png
<img width="1920" height="901" alt="Screenshot_2026-03-31_08-41-23" src="https://github.com/user-attachments/assets/4455f6e9-127c-4764-b6b0-45ab8b3c102f" />




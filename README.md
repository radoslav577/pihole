# Pihole DNS Filtering HomeLab

## Description

The project implements a network-wide DNS filtering and monitoring solution using Pi-hole on a Raspberry Pi 5.
I am doing this project so I can expand my knowledge about homelabbing, Linux administration, DNS skills, and Raspberry Pi.

## Overview

It blocks ads, trackers, and malicious domains while providing detailed DNS logging and visibility.
This is the first addition to my homelab; it will be mainly used to monitor DNS traffic and strengthen security.
The Pi-hole is attached to my network over WiFi with the IP 192.168.0.10 and is responsible for all the devices in my network.

## Hardware and Network

- Raspberry Pi 5 (16GB RAM)
- Storage(64gb microSD)
- Connection type(WiFi)
- Router model(Tp-Link EX220)
- Static IP address: 192.168.0.10

## Setup Steps

1. Flash the SD card with Raspberry Pi OS
   - Used Raspberry Pi Imager to install the OS onto the SD card.

2. Connect to the Pi using SSH
   - Connected over WiFi using the terminal with the assigned IP address, username, and password.

3. Set a static IP
   - Set a static IP for the Raspberry Pi in the router settings.

4. Install the Pi-hole software
   - Installed Pi-hole using the command presented on the official Pi-hole website.

5. Configure router Primary DNS
   - Set the Pi-hole IP address as the Primary DNS in the router.

6. Verify filtering works
   - Used the Pi-hole query log to confirm DNS traffic and verify that filtering is working.

## What I Learned

- This project helped me learn more about Linux administration.
- Working with static DNS, DHCP, and IP configuration.
- How to configure a router and manage headless hardware.
- Security basics, such as blocking malicious domains.
- Reading and interpreting Pi-hole logs.

## Screenshots

<img width="1919" height="1080" alt="pihole3" src="https://github.com/user-attachments/assets/9d6f141d-5e87-4124-8180-f6155f8e7bc0" />
<img width="952" height="1080" alt="pihole2" src="https://github.com/user-attachments/assets/f0cb821e-4fe6-4633-b55d-5fb2d7e0867b" />
<img width="956" height="1079" alt="pihole1" src="https://github.com/user-attachments/assets/b650d4e7-6d57-4eb9-8a1e-2ac504e76881" />

## Future Improvements

- Connect the Raspberry Pi with Ethernet cable for more stable Pi-hole operation.
- Add Unbound to turn Pi-hole into a recursive DNS resolver.










---
title: "Home Lab Specs and Plans"
author: hunter
date: 2024-01-01 11:43:00 -0500
categories: [HomeLab, Server]
tags: [homelab, dell-r730, unraid, server]
---

The Dell R730 handles the bigger jobs, while a Lenovo M900 runs the services I want available around the clock. I'm also planning a smaller server to bridge the gap.

## Dell R730

- iDRAC Enterprise
- All three risers 
- Two 1,100 W power supplies
- 10 Gb networking 
- Two E5-2683 v4 CPUs 
- 128 GB DDR4 ECC 2400 MHz (4 × 32 GB) 
- 16 bays, with four 1 TB Samsung 870 SSDs
- H730P
- GTX 1070

Connected to a Dell MD1200 via a Dell H810:
- MD1200
- Twelve 3.5-inch HGST 8 TB, 7,200 RPM drives

The R730 runs Unraid and Jellyfin. Because it draws more power, I moved the services that need to stay online 24/7 to a Lenovo M900.

## Lenovo M900

- 256 GB Samsung 870 EVO
- 32 GB non-ECC RAM
- i7-6700

The M900 runs:
- Vaultwarden
- Mealie
- Cloudflare
- This website
- Portainer
- CasaOS
- Guacamole

I plan to move the M900 services to my original server in a 2U chassis so I can use ECC memory.

## Original Server

Its current parts are:
- Supermicro X10SAE
- Intel Core i7 (model to confirm)
- 32 GB non-ECC DDR3 RAM
- 250 GB Samsung 870 EVO
- An old mid-tower case I already had

For the rebuild, I'm considering:
- Supermicro X10SAE
- Xeon E3-1285L v4
- 32 GB DDR3 ECC RAM
- A Dell H830 RAID controller in HBA mode, pending compatibility research. I'd like to improve the storage link, but I need to verify what the MD1200 and controller actually support.

I'd also like to replace the GTX 1070 in the R730 with an RTX A2000 for more transcoding headroom. I still need to test how many simultaneous streams the setup can handle.

The goal is to keep Vaultwarden, this website, Mealie, and Jellyfin running on the lower-power server. I'd use the R730 for heavier jobs such as video conversion with Tdarr. Even with a lot of storage, I'd rather avoid wasting it.

I still need to work out how the two systems will share access to the files. The current plan is Proxmox on the R730 and Unraid on the lower-power server. I also want to move my Unraid boot drive to a Samsung Bar Plus 128 GB USB stick; the current no-name 32 GB stick has been around since I was in seventh grade.

Proxmox would make it easier to spin up virtual machines and try new environments as I learn more in my field.

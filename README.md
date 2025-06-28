I'm ~~new~~ to home labs, where I'm constantly striving to enhance my skills and knowledge. This repository contains resources from my personal entry-level home lab.

![image](https://github.com/user-attachments/assets/4d43f866-4b30-4711-b355-6d0f63a1fefc)


### Hardware
#### Raspberry Pi 4 8GB
- 32GB SD Card storage
- Metal heatsink with 2 mini-fans

### Beelink Mini S12Pro
- 16GB DDR4 RAM
- Intel N100 CPU
- 512GB M2 SSD

### HP Proliant DL360P Gen 8 (Kinda old)
- 128GB DDR3 ECC RAM
- 2x E5-2640v2 CPU
- 2x 1.2TB Toshiba SAS HDD (Raid 1)
- 1X 500GB Toshiba SATA HDD
- 1x 500GB Crucial SATA SSD

#### Personal computer (Running VMs for optional testing other than personal use.)
- 32GB 3600MHz DDR4 Ram
- AMD Ryzen 5 3600x CPU
- RTX 2060 6GB GPU
- 512GB M2 SSD, 1TB M2 SSD, 1TB 2.5' HDD

#### Network
- Beelink U59 Running pfSense-ce (16Gb Ram 512GB SSD) 
- TP-Link Archer AX53 (Running in AP mode)
- TP-Link TG-108E 8 Port Switch
- 1GBps Upload/Download


### OS
- Ubuntu Server 22.04.3 LTS (Raspberry Pi & VMs on Personal Computer)
- Windows 11 23teH2 (Personal Computer)

### Containerization & Virtualization
- Proxmox VE
- VMWare Workstation Pro 17
- Docker

### Cloud
- 1x VPS With 2 Core and 4 Gig of Ram
  I know Cloud doesn't count for the home lab but at the end of the day I using it

### Apps & Services

#### Container Management
- [Portainer](https://portainer.io/) for managing containers.
  Cloud for managing containers running on cloud vps
- [Watchtower](https://github.com/containrrr/watchtower) for update container images.

#### Network
- [HAProxy](https://www.haproxy.com/) High Availability LoadBalancer and Reverse Proxy (Using instead of nginx proxy manager)
- [pfSense](https://www.pfsense.org/) Router/Firewall
- [Adguard Home](https://adguard.com/en/adguard-home/overview.html) Ad & Tracker Blocking and Dns-Over-Https

#### Monitoring
- [Uptime Kuma](https://uptime.kuma.pet/) Self-Hosted uptime monitor
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) internet speed monitoring
- [Dozzle](https://dozzle.dev/) for docker container logs (also use portainer for docker logs)

### Document & File Management
- [Immich](https://immich.app/) photo and video management
- [Paperless-ngx](https://docs.paperless-ngx.com/) Document manager
- [BookStack](https://www.bookstackapp.com/) Self hosted wiki
- [FileBrowser](https://filebrowser.org/) For access raspberry pi files everywhere

### Personal
- [Vikunja](https://vikunja.io/) to-do app
- [Actual Budget](https://actualbudget.org/) Budget tracker
- [Wallos](https://wallosapp.com/) Subscription tracker
- [Glance](https://github.com/glanceapp/glance) RSS Feed dashboard

#### Other
- [It-Tools](https://github.com/CorentinTh/it-tools) collection of online tools for developers (Still running but removed on homepage)
- [Shlink](https://shlink.io/) Self-Hosted link shortener app
- ~~[NTFY](https://ntfy.sh/) For get mobile push notifications~~
- ~~[Grafana](https://grafana.com/) For monitoring resources~~

#### [Homepage](https://gethomepage.dev/latest/)

### Planing for hardware
- MiniPC for virtualization
- NAS Server (Planning 2x4TB 2.5' SSD RAID 1)

# homelab
I'm new to home labs, where I'm constantly striving to enhance my skills and knowledge. This repository contains resources from my personal entry-level home lab.

![Untitled-1](https://github.com/uaerman/homelab/assets/34603648/bb9d83e1-ec70-4326-816b-8fc923e2eb3a)

### Hardware
#### Raspberry Pi 4 8GB
- 32GB SD Card storage
- Metal heatsink with 2 mini-fans

#### Personal computer (Running VMs for optional testing other than personal use.)
- 32GB 3600MHz DDR4 Ram
- AMD Ryzen 5 3600x CPU
- RTX 2060 6GB GPU
- 512GB M2 SSD, 1TB M2 SSD, 1TB 2.5' HDD

#### Network
- Gigabit ISP Router (For now)

### OS
- Ubuntu Server 22.04.3 LTS (Raspberry Pi & VMs on Personal Computer)
- Windows 11 22H2 (Personal Computer)

### Containerization & Virtualization
- VMWare Workstation Pro 17
- Docker with Portainer

### Cloud
- VPS With 4 Core and 4 Gig of Ram
  I know Cloud doesn't count for home lab but end of the day i using it

### Apps & Services

#### Container Management
- [Portainer](https://portainer.io/) for managing containers.
  Cloud for managing containers running on cloud vps
- [Watchtower](https://github.com/containrrr/watchtower) for update container images.

#### Network
- ~~[Nginx Proxy Manager](https://nginxproxymanager.com/) reverse proxy (for now I'm only using Cloudflare tunnel)~~ REMOVED
- [HAProxy](https://www.haproxy.com/) High Availability LoadBalancer and Reverse Proxy (Using instead of nginx proxy manager)
- [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) for public domain connection
- [Adguard Home](https://adguard.com/en/adguard-home/overview.html) Ad & Tracker Blocking and Dns-Over-Https

#### Monitoring
- [Uptime Kuma](https://uptime.kuma.pet/) Self-Hosted uptime monitor
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) internet speed monitoring
- [Dozzle](https://dozzle.dev/) for docker container logs (also use portainer for docker logs)

#### Other
- [It-Tools](https://github.com/CorentinTh/it-tools) collection of online tools for developers
- [Shlink](https://shlink.io/) Self-Hosted link shortener app
- [LinkAce](https://www.linkace.org/) Self-Hosted bookmark archive
- [Paperless-ngx](https://docs.paperless-ngx.com/) Document manager
- [qBitTorrent](https://www.qbittorrent.org/) Torrent Client
- [FileBrowser](https://filebrowser.org/) For access raspberry pi files everywhere
- [NTFY](https://ntfy.sh/) For get mobile push notifications

#### Why No Media
- I simply don't watch movies or series. :/

#### [Homepage](https://gethomepage.dev/latest/)

### Planing for hardware
- Replacing the ISP router with a new one, probably PfSense. (My current ISP allows to replacement of the router.)
- NAS Server (Planning 2x4TB 2.5' SSD RAID 1)

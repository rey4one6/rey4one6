 👋 Hi, I'm rey - i-use-arch-btw

### 🔧 Journeyman Pipefitter | Welder | 3rd-Year Plumber → Aspiring Cybersecurity Professional

I spent 11+ years in industrial shutdowns, maintenance, and new construction. Now I'm pivoting into cybersecurity with hands-on infrastructure and security engineering.

---

## 🧪 Homelab & Projects

### 🔐 Immutable Container Host (Fedora CoreOS + Podman + Quadlets)
- Architected a production-grade media automation stack on an immutable, container-optimized OS
- **Rootless Podman** with Quadlets — zero Docker daemon, zero root exposure
- **SELinux** enforcing mode for container isolation and mandatory access control
- **Tailscale WireGuard VPN** with SSO — zero ports exposed to the internet
- **3-2-1 backup strategy**: Proxmox daily snapshots → external drive, Duplicati → Backblaze B2, GitHub → IaC
- **Podman health checks** + ntfy.sh push notifications for real-time failure alerts
- **Version pinning** to prevent supply-chain attacks via unpinned container updates
- Full rebuild from bare metal to operational in **under 15 minutes** with Butane/Ignition

### 🐧 Container Migration & Platform Evaluation
- Migrated Docker Compose stack from Ubuntu Server to Fedora Server + Podman
- Evaluated security tradeoffs: daemonized vs. daemonless, root vs. rootless containers
- Wrapped entire stack in a single systemd service for lifecycle management

### 🎬 Media Automation Stack (Ubuntu + Docker → Fedora CoreOS)
- Sonarr, Radarr, Prowlarr, Bazarr, SABnzbd, Jellyfin, Jellyseerr, Maintainerr, Duplicati
- Automated quality profiles preferring x265 for space efficiency
- Smart media cleanup with Maintainerr (watched → delete, favorites/collections → keep)
- GPU passthrough evaluation (AMD 4600G APU) — documented limitations for iGPU virtualization

---

## 🛠 Tech Stack

![Fedora](https://img.shields.io/badge/-Fedora%20CoreOS-51A2DA?logo=fedora&logoColor=white)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Arch](https://img.shields.io/badge/-Arch%20Linux-1793D1?logo=archlinux&logoColor=white)
![NixOS](https://img.shields.io/badge/-NixOS-5277C3?logo=nixos&logoColor=white)
![Podman](https://img.shields.io/badge/-Podman-892CA0?logo=podman&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/-Proxmox-E57000?logo=proxmox&logoColor=white)
![Tailscale](https://img.shields.io/badge/-Tailscale-242424?logo=tailscale&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white)
![Jellyfin](https://img.shields.io/badge/-Jellyfin-00A4DC?logo=jellyfin&logoColor=white)
---

---

## 🔍 What I'm Learning

- Infrastructure-as-Code (Butane/Ignition)
- SELinux policy management
- Zero-trust networking (WireGuard/Tailscale)
- Container security hardening
- Supply-chain risk mitigation
- Security+ (in progress)

---

## 📫 Let's Connect

- 📧 rey4one6@email.com
- 🐙 [github.com/rey4one6](https://github.com/rey4one6)

---

*"From pipefitting to packet filtering — same troubleshooting mindset, different tools."*

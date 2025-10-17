# Home Lab Automation Stack – A Starter Guide

This repository contains Docker Compose configurations for a **complete personal home server setup**, designed to help anyone get started with homelabbing. Perfect for beginners who want to explore **Docker, automation, and self-hosted media**.

> Inspired for helping Redditors and home lab enthusiasts get their servers up and running safely.

---

## What’s Inside
- **Gluetun** – VPN container to secure your network and route traffic safely.  
- **Jellyfin** – Self-hosted media server to organize your movies, shows, and music.  
- **Radarr & Sonarr** – Automate your movie and TV show management.  
- **Prowlarr** – Indexer manager for all your automation tools.  
- **Jellyseerr** – Media request management (no media included).  
- **Other useful services** – Plex, Portainer, QBittorrent, Nginx, and more.

---

## ⚠️ Important Notes
- Set **PATHS** in **.env** for every service that requires them.
- All **sensitive information** (VPN credentials, API keys) are **not included** in this repo.  
- Some services may require **proxy access** through Gluetun. Use the address `gluetun:8888` where needed.  
- This repo **does not contain any copyrighted media**
- **You are responsible for your own setup**. I am not responsible for any damage, misconfigurations, or misuse.  
- The goal is to help others **set up and experiment** with homelabs, learn Docker, and understand service orchestration.

---

## How to Use
1. Clone the repo:
2. Create config files wherever necessary use each services's docker compose file for reference



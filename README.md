# Selfhosted Server Stack
My selfhosted docker stack which I use on my laptop for random services.

## Services
- ArchiSteamFarm: farms Steam cards and provides a CLI for Steam functions
- beets-flask: web UI for beets music library management & tagging
- Jellyfin: media streaming server for movies, TV, and music
- Immich: self-hosted photo and video backup & management
- Navidrome: self-hosted music streaming server
- Profilarr: custom format and profile management for Radarr/Sonarr
- Prowlarr: indexer management and search aggregator for the *arr stack
- qBittorrent: torrent client with web UI
- Radarr: movie collection automation and management
- Seerr: media request management for Jellyfin
- slskd: Soulseek music file sharing client
- Sonarr: TV series collection automation and management
- tsbridge: Tailscale mesh VPN integration for Docker containers

## Installation
### Prerequisites
- [Docker](https://docs.docker.com/engine/install/) and the [Docker Compose plugin](https://docs.docker.com/compose/install/)

### Setup
1. Copy `.env.example` to `.env` and populate the required variables:
2. Clone this repository and enter the directory:
   ```bash
   git clone https://github.com/ksharizard/selfhosted-server && cd selfhosted-server
   ```

3. Start all services:
   ```bash
   sudo docker compose up -d
   ```

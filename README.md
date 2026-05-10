# Selfhosted Server Stack

My selfhosted docker stack which I use on an old laptop for random services.

## Services
- ArchiSteamFarm: used to farm Steam cards and also acts as a CLI interface for Steam functions
- Dockhand: manages docker containers and stacks
- Navidrome: local music server

## Installation
1) Copy .env.example and make a .env, filling the required variables
2) Install docker and docker compose plugin
3) Pull this repository into a directory
4) `docker compose up -d`

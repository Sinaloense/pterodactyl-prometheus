# pterodactyl-prometheus
Dockerfile and Egg to run Prometheus inside a Pterodactyl server.

## Repository contents

- `Dockerfile` — Image with cloudflared and required scripts. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/Dockerfile)
- `entrypoint.sh` — Startup script. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/entrypoint.sh)
- `egg-prometheus.json` — Egg to use in Pterodactyl.

## Features

- Prometheus version: `3.10.0`.

## Requirements

- Pterodactyl installed.

## Installation

- Upload `egg-prometheus.json` to your Pterodactyl panel.

## Recommended to be used together with

- [Pterodactyl Cloudflared.](https://github.com/Sinaloense/pterodactyl-cloudflared)

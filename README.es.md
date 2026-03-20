# pterodactyl-prometheus
Dockerfile y Egg para correr Prometheus dentro de un servidor Pterodactyl.

## Contenido del repositorio:

- `Dockerfile` — Imagen con Nginx, PHP-FPM y scripts necesarios. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/Dockerfile)
- `entrypoint.sh` — Script de arranque. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/entrypoint.sh)
- `egg-prometheus.json` — Egg para usar en Pterodactyl.

## Características

- Prometheus version: `3.10.0`.

## Requisitos:

- Pterodactyl installed.

## Instalación:

- Carga `egg-prometheus.json` en tu panel.

## Recomendado usarse en conjunto con:

- [Pterodactyl Cloudflared.](https://github.com/Sinaloense/pterodactyl-cloudflared)

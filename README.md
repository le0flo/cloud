# Cloud

Compose files for my home cloud.

## General

Environment variables:

- `COMPOSE_FILE`
- `CLOUD_HOST`

## Website

Port: `9000`

Environment variables: *None*

Volumes: *None*

## Navidrome

Port: `9001`

Environment variables: *None*

Volumes:

- `navidrome-data`

## Immich

Port: `9002`

Environment variables:

- `IMMICH_DB_USERNAME`
- `IMMICH_DB_PASSWORD`

Volumes:

- `immich-cache`
- `immich-database`
- `immich-data`

## Paperless

Port: `9003`

Environment variables:

- `PAPERLESS_SECRET_KEY`

Volumes:

- `paperless-cache`
- `paperless-data`
- `paperless-media`
- `paperless-export`
- `paperless-consume`

## Jellyfin

Port: `9004`

Environment variables: *None*

Volumes:

- `jellyfin-cache`
- `jellyfin-config`

## qBittorrent

Port: `9005`

Environment variables: *None*

Volumes:

- `qbittorrent-config`

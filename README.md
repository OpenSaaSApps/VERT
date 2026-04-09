# VERT

> Click To Deploy VERT — Browser-based File Converter

[![Sync](https://github.com/opensaasapps/VERT/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/VERT/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/VERT/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/VERT/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/VERT)](https://hub.docker.com/r/thefractionalpm/VERT)

Upstream: [VERT-sh/VERT](https://github.com/VERT-sh/VERT) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `PORT` | ⚪ | |
| `PUB_HOSTNAME` | ⚪ | |

## Image

```
docker pull ghcr.io/vert-sh/vert:latest
docker pull thefractionalpm/VERT:latest
```

## Ports

| Port | Service |
|---|---|
| `3000` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*

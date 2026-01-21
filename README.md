# Calibre Web

A self-hosted application for managing calibre-web.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/calibre-web/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/calibre-web" ~/.local/srv/docker/calibre-web
cd ~/.local/srv/docker/calibre-web
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install calibre-web
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.

# Docker

## Networks

```bash
docker network create www
docker network create --internal intranet
```

## Container

### Deployment
```bash
cd <folder>
touch .env #put each var vom docker-compose into this file
docker-compose up -d
```
### Update
```bash
docker-compose pull
docker-compose up -d
```
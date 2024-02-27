# docker-vpn-wireguard

### Install

```bash
apt update && apt upgrade -y
apt install docker.io
apt install docker-compose
```

### Run docker container

```bash
docker-compose up -d
docker exec -it wireguard /app/show-peer 1
```
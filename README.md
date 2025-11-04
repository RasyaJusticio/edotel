# Edotel

## Running locally

### Docker

Starting

```
docker compose -f docker-compose.dev.yml up --build
```

Stopping

```
docker compose -f docker-compose.dev.yml down
```

Accessing the environment inside docker

```
sudo docker compose -f docker-compose.dev.yml exec app bash
```

## Deploying on a server

### Docker

```
docker compose -f docker-compose.dev.yml up --build
```

Don't forget to run the usual commands like migrate and generating the encryption key inside the `app` container


# Keycloak Docker setup with MariaDB

A Keycloak setup for development and production.

## Guide

### Build the custom docker image

```docker build . -t keycloak_image```

### Development
```docker compose up -d```

### Production
```docker compose -f docker-compose.yml -f docker-compose.prod.yml --env-file .env.prod up -d```

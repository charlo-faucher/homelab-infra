# homelab-infra


## Demarring the services

### Komga
```bash
docker compose --env-file .env -f komga/compose.yaml up -d
```


### Home Assistant
```bash
docker compose --env-file .env -f homeassistant/compose.yaml up -d
```


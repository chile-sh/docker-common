# Docker common

Common services used by [chile.sh](https://chile.sh)

```bash
cp .env.example .env

# Development
docker-compose up -f docker-compose.yml -f docker-compose.dev.yml

# Production
docker-compose up -f docker-compose.yml -f docker-compose.prod.yml
```

# License

MIT

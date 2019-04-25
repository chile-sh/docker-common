# Docker common

Common services used by [chile.sh](https://chile.sh)

```bash
cp .env.example .env

# Development
docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d

# Production
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
```

# License

MIT

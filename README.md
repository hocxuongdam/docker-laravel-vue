# docker-vue-project

This template should help get you started developing with Vue 3 in Vite.
With docker + hot reload

## Requirements
- Docker & Docker Compose

## Project Setup

```sh
docker compose up
```

Login into app-php container
```sh
composer install
```

Open http://localhost:5173/

### Initialize database
```
Add SQL into init_db.sql
```

## Docker structure
- New images:
  - app-img-php
  - app-img-frontend

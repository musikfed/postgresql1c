# docker-postgrespro-1c

Docker image for PostgreSQL/Postgres Professional intended for use with 1C:Enterprise server workloads. The repository contains build/run scripts and PostgreSQL configuration for a containerized database.

## Architecture / Архитектура

```text
1C:Enterprise server -> PostgreSQL protocol -> Postgres Professional container -> Docker volume with database data
```

## Project structure / Структура проекта

- `container/` — PostgreSQL container configuration
- build/run scripts — image build and lifecycle helpers
- Docker volume — persistent PostgreSQL data

## Contact / Контакты

- Email: feudor.lab@yandex.ru
- Telegram: @Feudorlab1

# docker-postgrespro-1c

1C:Enterprise серверин кытта үлэҕэ анаммыт PostgreSQL/Postgres Professional Docker образ. Репозиторийга контейнер базаҕа build/run скриптэр уонна PostgreSQL конфигурацията баар.

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

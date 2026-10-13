# docker-postgrespro-1c

1C:Enterprise серверімен жұмыс істеуге арналған PostgreSQL/Postgres Professional Docker образы. Репозиторийде контейнерлік дерекқорға арналған build/run скрипттері мен PostgreSQL конфигурациясы бар.

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

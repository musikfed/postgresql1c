# docker-postgrespro-1c

Docker-вобраз PostgreSQL/Postgres Professional для працы з серверам 1C:Enterprise. Рэпазіторый змяшчае скрыпты зборкі/запуску і канфігурацыю PostgreSQL для кантэйнернай базы.

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

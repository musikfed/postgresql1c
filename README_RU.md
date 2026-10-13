# docker-postgrespro-1c

Docker-образ PostgreSQL/Postgres Professional для работы с сервером 1С:Предприятия. Репозиторий содержит скрипты сборки/запуска и конфигурацию PostgreSQL для контейнерной базы данных.

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

# docker-postgrespro-1c

用于 1C:Enterprise 服务器场景的 PostgreSQL/Postgres Professional Docker 镜像。仓库包含容器化数据库的构建/运行脚本与 PostgreSQL 配置。

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

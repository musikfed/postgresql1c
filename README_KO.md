# docker-postgrespro-1c

1C:Enterprise 서버와 함께 사용하기 위한 PostgreSQL/Postgres Professional Docker 이미지입니다. 컨테이너형 데이터베이스용 빌드/실행 스크립트와 PostgreSQL 설정을 포함합니다.

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

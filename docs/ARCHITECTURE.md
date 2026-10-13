# Architecture / Архитектура

```text
1C:Enterprise server -> PostgreSQL protocol -> Postgres Professional container -> Docker volume with database data
```

- `container/` — PostgreSQL container configuration
- build/run scripts — image build and lifecycle helpers
- Docker volume — persistent PostgreSQL data

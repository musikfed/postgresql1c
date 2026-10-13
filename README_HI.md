# docker-postgrespro-1c

1C:Enterprise सर्वर के साथ उपयोग के लिए PostgreSQL/Postgres Professional का Docker इमेज। रिपॉज़िटरी में कंटेनर डेटाबेस के लिए build/run स्क्रिप्ट और PostgreSQL कॉन्फ़िगरेशन हैं।

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

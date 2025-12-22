# Rate Limiter - Ограничитель запросов

Видео с написанием кода и объяснениями: https://www.youtube.com/watch?v=UmtRivZfmX8

### Описание
Минимальное FastAPI приложение, показывающее, как ограничивать запросы к эндпоинтам через Redis.

## Локальный запуск
1. `docker compose up -d redis_container` — поднять Redis и GUI (опционально).
2. `uv pip sync` — установить зависимости из `pyproject.toml`.
3. `uvicorn main:app --reload` — запустить API и тестировать эндпоинты `/sql_code` и `/python_code`.

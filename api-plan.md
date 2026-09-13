# План API

## Endpoints
- GET /notes — список заметок
- POST /notes — создать заметку
- GET /notes/{id} — получить заметку
- PUT /notes/{id} — обновить заметку
- DELETE /notes/{id} — удалить заметку
## Модель данных
- Note: id, title, body, tags, created_at
- Tag: id, name

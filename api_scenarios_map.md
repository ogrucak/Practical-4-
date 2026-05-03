# API Scenarios Map — Mini-CRM Contacts API

| Endpoint | Успіх (код) | Помилка (код) | Що означає |
|----------|------------|--------------|-------------|
| GET /contacts | 200 | 401 / 500 | Отримання списку контактів |
| POST /contacts | 201 | 400 / 401 | Створення нового контакту |
| GET /contacts/{contactId} | 200 | 404 | Отримання контакту за ID |
| PUT /contacts/{contactId} | 200 | 404 / 400 | Повне оновлення контакту |
| PATCH /contacts/{contactId} | 200 | 400 / 404 | Часткове оновлення контакту |
| DELETE /contacts/{contactId} | 200 | 404 | Видалення контакту |
| GET /contacts/search?q=... | 200 | 400 / 401 | Пошук контактів |
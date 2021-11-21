# Аутентификация

Аутентификация зависит от правильной установки заголовков в каждом запросе со следующими данными:

- **Accept** и **Content-Type** должны быть `application/json`.
- **Authorization** - это API ключ вашего приложения, должен быть `Bearer [YOUR_API_KEY]`.

## Пример запроса

- API Key: `YOUR_API_KEY`
- `GET` запрос к `https://api.melle.online/api/v1/opencart/ping`

## Пример заголовков

```
Accept: application/json
Content-Type: application/json
Authorization: Bearer YOUR_API_KEY
```

## Базовый URL

```
https://api.melle.online/api/v1/opencart/
```

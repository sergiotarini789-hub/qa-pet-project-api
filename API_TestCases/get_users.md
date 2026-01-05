# Test Case: Get list of users

Endpoint:
GET https://reqres.in/api/users?page=1

Шаги:
1. Отправить GET запрос

Ожидаемый Результат:
- Status code 200
- Response body не пустой
- Поле "data" содержит массив пользователей
- Каждый пользователь имеет поля:
  - id (number)
  - email (string)
  - first_name (string)
  - last_name (string)

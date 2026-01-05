# Test Case: Get list of users

Endpoint:
GET https://reqres.in/api/users?page=1

Шаги:
1. Отправить GET запрос

Ожидаемый результат:
- Status code 200
- Response body содержит список пользователей
- Каждый пользователь имеет поля id, email, first_name, last_name

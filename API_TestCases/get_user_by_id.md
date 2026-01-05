# Test Case: Get user by valid ID

Endpoint:
GET https://reqres.in/api/users/2

Шаги:
1. Отправить GET запрос

Ожидаемый Результат:
- Status code 200
- Response body содержит объект пользователя
- Поле id равно 2
- Поля email, first_name, last_name присутствуют

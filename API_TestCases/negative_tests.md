# Test Case: Get user with invalid ID

Endpoint:
GET https://reqres.in/api/users/9999

Ожидаемый результат:
- Status code 404
- Response body содержит сообщение об ошибке или пустой объект

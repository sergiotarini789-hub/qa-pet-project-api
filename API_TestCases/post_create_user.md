# Test Case: Create new user

Endpoint:
POST https://reqres.in/api/users

Request Body:
{
  "name": "John",
  "job": "QA Engineer"
}

Expected Result:
- Status code 201
- Response body содержит id и createdAt

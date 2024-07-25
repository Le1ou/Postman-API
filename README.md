1.Register User

POST https://blog.kata.academy/api/users Body: { "user": { "username": "Ilya", "email": "shipa1337o@inbox.ru", "password": "987654321" } }

2.Login User

POST https://blog.kata.academy/api/users/login Body: { "user": { "email": "shipa1337o@inbox.ru", "password": "987654321" } }

3.Current User

GET https://blog.kata.academy/api/user Authorization Token "my_token"

Response: { "user": { "username": "Ilya", "email": " "shipa1337o@inbox.ru", "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY2YTBhYzNmZWYwMzkxMWIwMGFlZWE5MiIsInVzZXJuYW1lIjoiaWx5YSIsImV4cCI6MTcyNjk5MDc5MSwiaWF0IjoxNzIxODA2NzkxfQ.ZZhDdournF1HiF7riqeStWuTOO5fYbB6tyh8CI4-q_8" } }
![Регистрация](https://github.com/Le1ou/Postman-API/blob/c2e5a4deffeaa7413f501b1fef903ebc795cf3de/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2025-07-2024%20115014.jpg)
![Аутонтефикация](https://github.com/Le1ou/Postman-API/blob/c2e5a4deffeaa7413f501b1fef903ebc795cf3de/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2025-07-2024%20115052.jpg)
![Get-запрос]https://github.com/Le1ou/Postman-API/blob/c2e5a4deffeaa7413f501b1fef903ebc795cf3de/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2025-07-2024%20115214.jpg

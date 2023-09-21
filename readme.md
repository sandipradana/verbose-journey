### register
```
curl -X POST -H "Content-Type: application/json" -d '{"name" : "Sandi Pradana", "email": "sandipradana@hotmail.com", "password": "passwordkuh"}' http://localhost:3000/api/register
```

### login
```
curl -X POST -H "Content-Type: application/json" -d '{"email": "sandipradana@hotmail.com", "password": "passwordkuh"}' http://localhost:3000/api/login
```

### me
```
curl -H "Authorization: Bearer your_token" http://localhost:3000/api/me
```
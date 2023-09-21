### register
```
curl -X POST -H "Content-Type: application/json" -d '{"name" : "Sandi Pradana", "email": "sandipradana@hotmail.com", "password": "passwordkuh"}' https://verbose-journey.vercel.app/api/register
```

### login
```
curl -X POST -H "Content-Type: application/json" -d '{"email": "sandipradana@hotmail.com", "password": "passwordkuh"}' https://verbose-journey.vercel.app/api/login
```

### me
```
curl -H "Authorization: Bearer your_token" https://verbose-journey.vercel.app/api/me
```
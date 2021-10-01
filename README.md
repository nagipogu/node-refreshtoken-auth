# node-refreshtoken-auth

Start project: npm run dev

installations: npm i express jsonwebtoken nodemon cors

1.http://localhost:5000/login(POST) 
inputs:
{"user": { "email": "ysr@gmail.com", "password": "giri@123" } }

2.http://localhost:5000/protected(POST) 
headers: 
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpYXQiOjE2MzMwODk3NjIsImV4cCI6MTYzMzA4OTc4Mn0.8cPwg_MNM8KcQgriMhDFxtu-SbL1h1lGupRCsxP79Q0 
inputs:

3.http://localhost:5000/refresh(POST) 
inputs: 
{ "token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InlzckBnbWFpbC5jb20iLCJwYXNzd29yZCI6ImdpcmlAMTIzIiwiaWF0IjoxNjMzMDg5NzI1LCJleHAiOjE2MzM2OTQ1MjV9.tfYqaFyxV_ckYnws1e2Ji8x3LD6L9LcwEjZ5-T9x_kc" }

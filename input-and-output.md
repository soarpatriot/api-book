
### input and output 

```
GET /users?age=20&weight=70 HTTP/1.1
```

```
POST /users http/1.1
HOST: api.example.com 
Authentication: bear 
Content-Type: appliction/json
{"name":"xiao"}
```

response
```
HTTP/1.1 200 ok 
Server: nginx
Content-Type: application/json
Connection: close

{
  "id":1690
  "name":"xiaoxiao"
}

```

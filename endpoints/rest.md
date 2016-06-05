

###Before
``` 
POST /SendUserMessage HTTP/1.1
Host: example.com
Content-Type: application/x-www-form-urlencoded

id=5&message=hello
``` 

###Now Rest
```
POST /users/5/send-message HTTP/1.1
Host: example.com
Content-Type: application/json
{"message": "hello world!"}
```

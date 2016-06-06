

###Before
``` 
POST /SendUserMessage HTTP/1.1
Host: example.com
Content-Type: application/x-www-form-urlencoded

id=5&message=hello
``` 

###Now Rest

Where is the problem below?
```
POST /users/5/send-message HTTP/1.1
Host: example.com
Content-Type: application/json
{"message": "hello world!"}
```

REST: Representational state transfer
1. http 
2. http method 
3. content negotiation


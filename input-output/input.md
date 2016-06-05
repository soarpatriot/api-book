
###input is strightforward




```
1 POST /moments/1/gift HTTP/1.1
2 Host: api.example.com
3 Authorization: Bearer vr5HmMkzlxKE70W1y4MibiJUusZwZC25NOVBEx3BD1
4 Content-Type: application/json
5 { "user_id" : 2 }”

```
###example

```
RestClient::Request.execute(method: :get, url: 'http://example.com/resource',
                            timeout: 10, headers: {params: {foo: 'bar'}})
```

###danger

do not mix json and string
```
“json="{
     \"checkin\": {
         \"place_id\" : 1,
         \"message\": \"This is a bunch of text.\",
         \"with_friends\": [1, 2, 3, 4, 5]
     }
}”

```


###Api security styles

1. http basic
Never use it, even over https
2. Digest Authentication
HA1 = MD5(username:realm:password) 

```
it still requires the username and password to be sent repeatedly, meaning it
is potentially hackable if the hacker has enough encrypted requests available to
process
```
3.OAuth1

![image](https://raw.githubusercontent.com/soarpatriot/api-book/master/images/oauth1.png)


4.OAuth2

![image](https://raw.githubusercontent.com/soarpatriot/api-book/master/images/oauth2.png)

### reality 

1.sign auth  example: some taobao apis
```
  sign = md5(api_key + api_secret + sorted_params + timestamp)
  send params:  sorted_params, timestamp, api_key, sign
```

2.some similar oauth2 
```
  pre: use https 
  request with: api_key, api_secret,  response:  access_token, refresh_token, expired_at
  use access_token get the resource
```


  

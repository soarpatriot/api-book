

### styles
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

```
(1) request   request token 
(2) request   access token 
(3) request resource with access token
```

4.OAuth2

```
(1) request   authrizon code
(2) request   access token 
(2) request   resource 
```

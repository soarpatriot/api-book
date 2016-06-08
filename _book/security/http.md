

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

![image](https://raw.githubusercontent.com/soarpatriot/api-book/master/images/oauth1.png)


4.OAuth2

![image](https://raw.githubusercontent.com/soarpatriot/api-book/master/images/oauth2.png)


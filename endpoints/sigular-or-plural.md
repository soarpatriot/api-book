
###sigular or plural
>>“Some developers decide to make all endpoints singular, but I take issue with this. Given /user/1 and /user, which user is that last one returning? Is it “me”? What about /place? It returns multiple? Confusing.”

>>摘录来自: Phil Sturgeon. “Build APIs You Won't Hate”。 iBooks. 


###plural
```
“I pick plural for everything as it is the most obvious:

/places - “If I run a GET on that, I will get a collection of places”
/places/45 - “Pretty sure I am just talking about place 45”
/places/45,28 - “Ahh, places 45 and 28, got it”
”
```


###Verb vs None
Post /users/5/send-message

A verb is an action - a doing term - and our API only needs one verb - the HTTP Method. All other verbs need to stay out of the URL.
A noun is a place or a thing. Resources are things, and a URL becomes the place on the Internet where a thing lives.




#REST Maturity
1. level0  "Swamp" user http as transfer prot , soap, xml-rpc
2. level1  "Resources" web under resources like   /users 
3. level2  "Http Verbs" web resouces under proper http method and http status 
4. level3  "Hypermedia Controls" HATEOAS client can find the resources and action from the link 

example of HATEOAS 
```
{
   "list": {
       "id": 1,
       "name": "Default"
   },
   "links": [
       {
           "rel": "self",
           "href": "http://localhost:8080/lists/1"
       },
       {
           "rel": "items",
           "href": "http://localhost:8080/lists/1/items"
       }
   ]
}
```

### some intresting about RESTful 

>> Roy Fielding says that without hypermedia controls an API is not RESTful, writing back in 2008. People have been ignoring that ever since, and the last estimate was that 74% of APIs claiming to be “RESTful” do not actually use hypermedia


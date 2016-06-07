
###relations
```
{
  "posts":[
    {
      "id":12,
      "title": "foo"
      "comments":[...]
    },
    {
      "id":13,
      "title": "foo"
      "comments":[...]
    }

   ]
}
```

###try to avoid some 1+n problem
```
{
  
  "data":[
    {
      "content": "sf"
      "comment_id": 1
    },
    {
      "content": "dt"
      "comment_id": 2
    }
  ]
    
  
}
```

###embeded data 
try to include more information when needed
/places?include=checkins,merchant
```
{
  "id":1,
  "name": "US",
  "merchant":[],
  "checkins":[]
}
```




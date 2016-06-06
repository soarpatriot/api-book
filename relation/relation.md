
###relation try to avoid some 1+n problem
```
{
  "posts":[
    {
     "id":12,
     "title": "foo"
    },
    {
     "id":13,
     "title": "foo"
    }

   ]
}
{
  
  "post_id":12
  "data":[
    {
      "content": "sf"
    },
    {
      "content": "dt"
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




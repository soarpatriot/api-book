

### pagination 
```
{
  "data":[...]
  "pagination": {
    "total": 1000,
    "count":12,
    "per_page":12,
    "current_page":1,
    "total_pages": 84
    "next_url": "/places?page=2&number=12"
  }
}

{
  "data":[...]
  "pagination": {
    "cursors":{
      "after":12,
      "next_url": "/places?cursor=12&number=12"
    }
  }
}

{
  "data":[...]
  "pagination": {
    "cursors":{
      "after":24,
      "before":12,
    }
  }
}


```

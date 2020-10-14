---
title: API
---

Here are some examples of request that can be made.

##### Example 1

```bash
curl --location --request GET 'https://peopleapi.netlify.app/people/index.json'
```

returns

```json
{
  "data": {
    "section": "people",
    "count": "3",
    "items": [
      {
        "name": "Misaka Mikoto",
        "description": "Railgun",
        "permalink": "/people/person/5ceabd30-0d4e-11eb-87e1-93227015a5ce/",
        "date": "2020-10-13 12:19:38.463 +0000 UTC"
      },
      {
        "name": "Spongebob",
        "description": "A sponge",
        "permalink": "/people/person/6dafb450-0d48-11eb-bfcf-a1b1553356f9/",
        "date": "2020-10-13 11:37:09.602 +0000 UTC"
      },
      {
        "name": "Darth Vader",
        "description": "i am not your father.",
        "permalink": "/people/person/6168dc00-0d32-11eb-8631-73b0acfc0ada/",
        "date": "2020-10-13 08:59:19.999 +0000 UTC"
      }
    ]
  }
}
```

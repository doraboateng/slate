## Search languages

> Sample request

```shell

```

```javascript
// Sample response
{
  "results": [
    {
      "code": "twi",
      "parentCode": "aka",
      "name": "Asante Twi",
      "altNames": "Ashanti, Twi",
      "createdAt": "2015-04-09 13:08:27",
      "updatedAt": "2017-05-08 22:58:14",
      "score": 0.97,
      "parentName": "Akan",
      "uniqueId": 1627566552,
      "resourceType": "language"
    },
    {
      "code": "aka",
      "parentCode": "",
      "name": "Akan",
      "altNames": " Twi",
      "createdAt": "2015-04-09 13:07:43",
      "updatedAt": "2017-03-09 23:54:36",
      "score": 0.18,
      "parentName": "",
      "uniqueId": 278921839,
      "resourceType": "language"
    }
  ]
}

// Sample compact response
{
  "twi": "Asante Twi",
  "aka": "Akan"
}
```

```php
<?php

// ...
```

> Sample response

```json

```

`GET /languages/search`

| Parameter | Contents |
| --- | --- |
| **format** (optional) | `[string]` Set to `compact` to receive a list of code-name pairs. |
| **q** (required) | `[string]` Search query. |

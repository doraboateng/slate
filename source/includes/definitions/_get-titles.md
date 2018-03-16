## Retrieve definition titles

> Sample request

```shell

```

```javascript
// ...
```

```php
<?php
$titles = $client->get('/definitions/278921839/titles?format=compact');
```

> Sample response

```json
// Full response
[
	{
		"title": "ɔdɔ",
		"createdAt": "2017-03-11 10:12:20",
		"updatedAt": "2017-03-11 10:12:20",
		"uniqueId": 278921839
	},
	{
		"title": "dɔ",
		"createdAt": "2017-03-11 10:12:20",
		"updatedAt": "2017-03-11 10:12:20",
		"uniqueId": 1627566552
	}
]

// Compact response
[
	"ɔdɔ",
	"dɔ"
]
```

`GET /definitions/:id/titles`

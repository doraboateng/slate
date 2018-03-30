## Sample code

> Sample setup

```javascript
const API_HOST = 'https://api.doraboateng.com/0.6';

fetch(API_HOST).then(response => console.log(response));
```

```php
<?php
use GuzzleHttp\Client;

$client = new Client(['base_uri' => 'https://api.doraboateng.com/0.6/']);
```

```shell
$ BOATENG_API_HOST=https://api.doraboateng.com/0.6
$ curl $BOATENG_API_HOST
```

The Javascript code samples use the [fetch API]().
The PHP code samples use the [GuzzleHttp client](http://docs.guzzlephp.org/en/stable/).

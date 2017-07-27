# Authentication

> Pass a Bearer token in an Authorization header.

```shell
$ curl 'https://app.sunlight.is/api/endpoint' \
    -H 'Authorization: Bearer c38e1f24a1b71ece08d29a04fa3daa7d58e71a5d58b660ae8b802732d42bf90b'
```

Authentication is done through the API key that will be provided by sunlight support.

Requests are authenticated passing your API key as a bearer token in an authorization header.

<aside class="danger">
  Your API keys carry many privileges, so be sure to keep them secret! Do not share your secret API keys in publicly accessible areas such GitHub, client-side code, and so forth.
</aside>

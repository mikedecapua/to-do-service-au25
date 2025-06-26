---
layout: page
---

# Get all users

Returns an array of [`user`](user.md) objects that contains all users that have registered with the service.

## URL

```shell

{server_url}/users
```

## Parameters

None

## Request headers

None

## Request body

None

## Return body

```js
[
    {
        "lastName": "Smith",
        "firstName": "Ferdinand",
        "email": "f.smith@example.com",
        "id": 1
    },
    {
        "lastName": "Jones",
        "firstName": "Jillio",
        "email": "jlo.jones@example.com",
        "id": 2
    }
    ...
]
```

## Return status

| Status value | Return status | Description |
| ------------- | ----------- | ----------- |
| 200 | Success | Requested data returned successfully |
|  ECONNREFUSED | N/A | Service is offline. Start the service and try again. |

[← Back](README.md)

## Request:

```javascript
DELETE https://air.untill.com/api/air-bo/1/articles HTTP/1.1
content-type: application/json

{
    "id": [number],
}
```

## Response: 

If success:

```javascript
{
    "location": [ 23, 44 ], //array of locations ids in which articles was removed
    "id": [ 123, 4324, 5435 ] //array of ids of removed articles
}
```
In other case returns errors:

```javascript
{
    "errors": [
        String | Object
    ]
}
```

[← Back](README.md)
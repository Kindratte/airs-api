[← Back](README.md)

## Request: 

```javascript
POST https://air.untill.com/api/air-bo/1/pricelevel HTTP/1.1
content-type: application/json

{
    "state": 1,
    "data": {
        "name": String,
        "hq_id": String,
        "number": Number
    }
}
```

## Response: 

If success:

```javascript 
{
    "Status": "Ok",
    "StatusCode": 200,
    "Data": Number //created items id
}
```

In other case returns errors:

```javascript
{
    "Status": "Bad request",
    "StatusCode": 400,
    "Data": String
}
```

[← Back](README.md)
# User API Spec

## Register User

- Endpoint : POST /api/users

Request Body :

```json
{
  "username" : "ahmad",
  "password" : "rahasia",
  "name" : "Ahmad Luhur Pakerti"
}
```

Response Body (Success) :

```json
{
  "data" : "OK"
}
```

Response Body (Failed) :

```json
{
  "data" : "KO",
  "errors" : "Username must is not blank, ???"
}
```

## Login User

- Endpoint

```json
{
  "username" : "ahmad",
  "password" : "rahasia",
  "name" : "Ahmad Luhur Pakerti"
}
```

Response Body (Success) :

```json
{
  "data" : "OK"
}
```

Response Body (Failed) :

```json
{
  "data" : "KO",
  "errors" : "Username must is not blank, ???"
}
```

## Update User

## Get User

## Logout User
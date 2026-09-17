# API Authentication

## Overview

The API requires a bearer access token to authenticate requests to protected resources.

## Authentication Header

Include an authorization header in each request:

`Authorization: Bearer <access-token>`

## Example

```http
GET /users/123
Authorization: Bearer <access-token>
```

## Errors

A `401 Unauthorized` response indicates that the request does not contain valid authentication credentials.


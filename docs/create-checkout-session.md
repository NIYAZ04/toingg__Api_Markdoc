# Create Checkout Session

This endpoint allows you to create a checkout session.

## Endpoint

- **Path**: `/create-checkout-session`
- **Method**: `POST`

### Request Body

- **Content Type**: `application/json`

```json
{
  "apikey": "string"
}
```
## Responses
### Successful Response

    Code: 200

    Media Type: application/json

    Schema:

    json

    "string"

### Validation Error

    Code: 422

    Media Type: application/json

   
   

## Example Value:
``` Json
{
  "detail": [
    {
      "loc": [
        "string",
        0
      ],
      "msg": "string",
      "type": "string"
    }
  ]
}
```

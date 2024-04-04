# Send SMS

This endpoint allows you to send an SMS message using the Toingg API.

## Endpoint

- **Path**: `/send_sms/`
- **Method**: `POST`

### Parameters

| Name   | Description | Type   | In     |
|--------|-------------|--------|--------|
| apiKey | API key     | string | query  |

### Request Body

- **Content Type**: `application/json`

```json
{
  "name": "string",
  "phoneNumber": "string",
  "message": "string"
}
```



## Responses
### Successful Response

    uccessful Response

    Code: 200

    Media Type: application/json

    Schema:
    
    "string"

### Validation Error


    Code: 422

    Media Type: application/json


   ## Example Value:

   
``` json

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

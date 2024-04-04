# Make Toingg

This endpoint allows you to make a Toingg call.

## Endpoint

- **Path**: `/make_toingg/`
- **Method**: `POST`

### Parameters

| Name   | Description | Type   | In     |
|--------|-------------|--------|--------|
| apiKey | API key     | string | query  |

### Request Body

- **Content Type**: `application/json`

```json
{
  "campaign": "string",
  "name": "string",
  "phoneNumber": "string"
}
```


## Responses

### Successful Response

    Code: 200

    Media Type: application/json

    Schema:

    

    "string"

### Validation Error

    Code: 422
    Media Type: application/json





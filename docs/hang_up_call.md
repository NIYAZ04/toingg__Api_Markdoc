# Hang Up Call

This endpoint allows you to hang up a call using the Toingg API.

## Endpoint

- **Path**: `/hang_up_call/`
- **Method**: `POST`

### Parameters

| Name    | Description | Type   | In     |
|---------|-------------|--------|--------|
| callSid | Call SID    | string | query  |
| apiKey  | API key     | string | query  |

### Responses

#### Successful Response

- **Code**: 200
- **Media Type**: `application/json`
- **Schema**:  "String"


### Validation Error
    Code: 422

    Media Type: application/json

## Example Value
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
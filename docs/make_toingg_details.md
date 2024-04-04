# Make Toingg Details

This endpoint allows you to make a Toingg call with additional details.

## Endpoint

- **Path**: `/make_toingg_details/`
- **Method**: `POST`

### Parameters

| Name   | Description | Type   | In     |
|--------|-------------|--------|--------|
| apiKey | API key     | string | query  |

### Request Body

- **Content Type**: `application/json`

```json
{
  "campaignName": "string",
  "campaignScript": "string",
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

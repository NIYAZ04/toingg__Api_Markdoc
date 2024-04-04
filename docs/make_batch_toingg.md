# Make Batch Toingg

This endpoint allows you to make multiple Toingg calls in a batch.

## Endpoint

- **Path**: `/make_batch_toingg/`
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
  "numberList": [
    {
      "clientName": "string",
      "clientNumber": "string"
    }
  ]
}
```


## Responses
### Successful Response

    Code: 200

    Media Type: application/json

    Schema:

   

## Validation Error

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

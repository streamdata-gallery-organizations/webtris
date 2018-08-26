{
  "info": {
    "name": "WebTRIS Traffic Flow API Returns list of areas",
    "_postman_id": "80eca1c7-2c03-4b9b-82e7-e8e8137c43d9",
    "description": "Returns list of areas.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "6a1691d4-2cde-4b17-9f6f-4628e24a4ab7",
          "name": "Areas_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/areas"
              ],
              "variable": [
                {
                  "id": "version",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of areas."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b1857e7-77f9-4bf9-aeea-1e70b549edce"
            }
          ]
        }
      ]
    }
  ]
}
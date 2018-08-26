{
  "info": {
    "name": "WebTRIS Traffic Flow API Get selected sites",
    "_postman_id": "9a2c3e22-6869-4605-9d72-ad32de02d2d5",
    "description": "Get selected sites.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "d0f7944d-cea9-4172-8f59-a3bb92b953e0",
          "name": "Areas_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/areas/:area_Ids"
              ],
              "variable": [
                {
                  "id": "area_Ids",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Returns details of selected area."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fd53ecd-cb10-4bb2-b95a-01c382926572"
            }
          ]
        }
      ]
    },
    {
      "name": "Selected",
      "item": [
        {
          "id": "286b4834-9642-4a4c-9404-7d82aeec6403",
          "name": "Sites_Index",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/sites/:site_Ids"
              ],
              "variable": [
                {
                  "id": "site_Ids",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get selected sites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02ce4c62-984f-4460-9357-475f08bdf813"
            }
          ]
        }
      ]
    }
  ]
}
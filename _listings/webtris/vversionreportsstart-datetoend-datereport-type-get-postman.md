{
  "info": {
    "name": "WebTRIS Traffic Flow API Gets the daily report.",
    "_postman_id": "eb49458c-223b-428d-b96d-54690cb4c3de",
    "description": "Gets the daily report..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "S",
      "item": [
        {
          "id": "126003bc-d9f2-432d-a731-0e774dcc2e0a",
          "name": "Reports_Index",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/reports/:report_type"
              ],
              "query": [
                {
                  "key": "end_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page_size",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "reportSubTypeId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sites",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_type",
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
            "description": "Gets the daily report.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78935c46-a979-4756-9b89-22202b40b2e5"
            }
          ]
        },
        {
          "id": "13dc81d0-461b-484c-8b93-436ab0ad914f",
          "name": "Reports_Index1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/reports/:start_date/to/:end_date/:report_type"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page_size",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "reportSubTypeId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sites",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "end_date",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_type",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "start_date",
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
            "description": "Gets the daily report.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95871665-1544-46b9-b256-fc0b9dff6d39"
            }
          ]
        }
      ]
    }
  ]
}
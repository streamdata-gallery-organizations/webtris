{
  "info": {
    "name": "WebTRIS Traffic Flow API Gets the daily report.",
    "_postman_id": "c31d3a67-437b-4b96-beb4-0ff280ae123e",
    "description": "Gets the daily report..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "S",
      "item": [
        {
          "id": "2d2eb9c4-b42d-49c7-9d13-38b77a4ae62a",
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
              "id": "835a48ff-bbc2-48cc-939d-d3a13b3b1f96"
            }
          ]
        }
      ]
    }
  ]
}
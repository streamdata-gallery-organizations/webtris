{
  "info": {
    "name": "WebTRIS Traffic Flow API Return list of site types",
    "_postman_id": "e923c93d-31b6-44d3-a639-011cbc616c3a",
    "description": "Return list of site types.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "4acc37fb-7dc1-465d-8995-1b141548ae26",
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
              "id": "9e8d21b5-4603-4205-baaf-26349c5a0110"
            }
          ]
        },
        {
          "id": "036f335e-9245-4155-a3fe-70132b7a18b6",
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
              "id": "3e2915f7-fb7f-4208-9033-626e32bb45e1"
            }
          ]
        }
      ]
    },
    {
      "name": "Site",
      "item": [
        {
          "id": "f438b6b7-6e77-483a-8229-018c3ee820b8",
          "name": "Quality_GetOverallDataQualityForSites",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/quality/overall"
              ],
              "query": [
                {
                  "key": "end_date",
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
            "description": "Get site overallquality."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88e147d5-793e-4489-9c0c-a7b120ff960f"
            }
          ]
        },
        {
          "id": "9d47e6ad-0f06-4591-8d6c-d4bb313628d3",
          "name": "Quality_GetDailyDataQualityForSite",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/quality/daily"
              ],
              "query": [
                {
                  "key": "end_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "siteId",
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
            "description": "Get site dailyquality."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b340722-8919-4766-9623-ec59a6e048de"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "81ca5f6f-59b2-4b97-ac4c-d11b8cf8d57c",
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
              "id": "cd78ed44-d84d-440c-b0b3-2cbab3df0ccf"
            }
          ]
        },
        {
          "id": "aa3e1ed4-f63d-4fef-b6b5-df23d4bada57",
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
              "id": "761997be-e8fc-4a61-9e68-ce1efcf549d0"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "c20ede64-e7c5-4bcb-8b11-9a53829eb87f",
          "name": "Sites_Index",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/sites"
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
            "description": "Get a list of sites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75fcd6b2-623e-4792-a411-6bcbbb60de33"
            }
          ]
        }
      ]
    },
    {
      "name": "Selected",
      "item": [
        {
          "id": "8dc3d05b-60fa-40b9-a10c-5cc1a23cb721",
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
              "id": "0f4b061a-0d43-4c5c-a3e3-021bccc221d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Return",
      "item": [
        {
          "id": "f5c6cd47-ec48-41c4-9250-9f4f6fade8ad",
          "name": "SiteTypes_Index",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/sitetypes"
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
            "description": "Return list of site types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e51b5aa-a693-4cb5-82e4-e8b5c4f97126"
            }
          ]
        }
      ]
    }
  ]
}
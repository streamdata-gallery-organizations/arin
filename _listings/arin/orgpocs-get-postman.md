{
  "info": {
    "name": "Organization API List POCs",
    "_postman_id": "f2d7c4f5-5236-413b-82b7-1c3b815e3612",
    "description": "lists the POCs associate with a given organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Organizations",
      "item": [
        {
          "id": "767ece33-fa88-4182-9119-625edd341d00",
          "name": "organizations",
          "request": {
            "url": "http://example.com/api/orgs?dba=dba&handle=handle&name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Manages organizations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a76d05f0-5629-4765-a783-df1de93100bc"
            }
          ]
        }
      ]
    },
    {
      "name": "POCs",
      "item": [
        {
          "id": "805d4519-e9f4-400d-8567-5b872942311a",
          "name": "orgPocs",
          "request": {
            "url": "http://example.com/api/org/pocs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the POCs associate with a given organization."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d6eaea5-4957-4bb7-bf68-4e414a3bed31"
            }
          ]
        }
      ]
    }
  ]
}
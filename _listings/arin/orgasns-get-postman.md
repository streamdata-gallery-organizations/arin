{
  "info": {
    "name": "Organization API List ASNS",
    "_postman_id": "41d9c642-26c1-48e0-be6b-4e7e7e56bf38",
    "description": "lists the ASNs associated with a given organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Organizations",
      "item": [
        {
          "id": "ac7b703f-3428-4740-9a04-068f3423e5f5",
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
              "id": "09cb0633-5195-432a-8954-b36ba64b1499"
            }
          ]
        }
      ]
    },
    {
      "name": "POCs",
      "item": [
        {
          "id": "38f3c139-7812-49d7-8e68-91d5a900acb2",
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
              "id": "71831d98-8f2b-487f-a8ba-ffb2775cdbd2"
            }
          ]
        }
      ]
    },
    {
      "name": "ASNs",
      "item": [
        {
          "id": "599d0cdc-24bf-45d0-bf97-b433e5beaa0b",
          "name": "orgAsns",
          "request": {
            "url": "http://example.com/api/org/asns",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the ASNs associated with a given organization."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7b39b4d-f66d-4a3e-a3ee-5de936bbb457"
            }
          ]
        }
      ]
    }
  ]
}
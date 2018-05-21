{
  "info": {
    "name": "Point of Contact (POC) API ASNs",
    "_postman_id": "a28ae88a-dc07-4f60-90e2-dbc7254fef61",
    "description": "lists the ASNs associated with a given POC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Point of Contact",
      "item": [
        {
          "id": "abcc3443-ae70-4c71-be19-21745479aa5c",
          "name": "poc",
          "request": {
            "url": "http://example.com/api/poc?city=city&company=company&domain=domain&first=first&handle=handle&last=last&middle=middle",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the Point of Contact (POC)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c598aa74-b40d-4942-b131-d438665992dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "a4f84076-764b-4824-8343-8d72697f0e17",
          "name": "pocOrg",
          "request": {
            "url": "http://example.com/api/poc/org",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the organizations associated with a given POC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afe62a3e-a122-4895-8015-b55d19fc650d"
            }
          ]
        }
      ]
    },
    {
      "name": "ASN",
      "item": [
        {
          "id": "b4cb9ed6-79df-4654-b46f-774135648743",
          "name": "pocAsns",
          "request": {
            "url": "http://example.com/api/poc/asns",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the ASNs associated with a given POC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82e8ec3d-0164-4cb8-8842-e557ce84d8c1"
            }
          ]
        }
      ]
    }
  ]
}
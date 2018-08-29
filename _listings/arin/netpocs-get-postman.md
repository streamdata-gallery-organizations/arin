{
  "info": {
    "name": "Network API List POCs",
    "_postman_id": "467bffc1-3a45-4ade-9462-6ed51d395e90",
    "description": "lists the POCs associated with a given network.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Networks",
      "item": [
        {
          "id": "e681ef07-c803-42fa-a0fe-f36521ba70e6",
          "name": "nets",
          "request": {
            "url": "http://example.com/api/nets?handle=handle&name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Networks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c54923ab-4149-4199-9abf-aa29c8487003"
            }
          ]
        }
      ]
    },
    {
      "name": "POCs",
      "item": [
        {
          "id": "b8fcd78b-70a4-4a8e-9980-e5a51f0d42c8",
          "name": "netsPocs",
          "request": {
            "url": "http://example.com/api/net/pocs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the POCs associated with a given network."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a376b6e-cf7a-42f5-bd3b-bdee952148a4"
            }
          ]
        }
      ]
    }
  ]
}
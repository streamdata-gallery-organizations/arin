{
  "info": {
    "name": "Delegation API Get Delegation",
    "_postman_id": "19fbc8e6-e667-4728-a5f0-57a0f9cb687b",
    "description": "This call will return a payload containing details about the Delegation specified in your URL.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Delegation",
      "item": [
        {
          "id": "28623487-62d5-42cf-8680-7f4bedd10688",
          "name": "getDelegation",
          "request": {
            "url": "http://www.arin.net/regrws/core/v1/delegation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call will return a payload containing details about the Delegation specified in your URL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89a1993e-7a51-4a45-a838-208fa36efd83"
            }
          ]
        }
      ]
    }
  ]
}
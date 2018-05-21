{
  "info": {
    "name": "Delegation API Add Delegation",
    "_postman_id": "32c8a6aa-b906-432e-88ca-795a15c3c9c0",
    "description": "This call will add the single nameserver specified in your URL to the Delegation specified in your URL, and return a payload containing that Delegation's information after the nameserver has been added.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Delegation",
      "item": [
        {
          "id": "27dd9f0b-1a43-462e-af38-3ef2a794075b",
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
              "id": "9fd8d766-35cb-4d5d-96b1-dbf1bb6377c2"
            }
          ]
        },
        {
          "id": "360e290a-ebb9-4c38-93f6-1f3a34728e7b",
          "name": "updateDelegation",
          "request": {
            "url": "http://www.arin.net/regrws/core/v1/delegation",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "This call will modify the details of the Delegation specified in your URL. When making this call, attach a Delegation Payload containing the details of the Delegation you intend to modify. To ensure accuracy, use Get Delegation to get the most current information before making changes. This call returns a payload containing that Delegation's information as it exists after modification."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f352df8-5202-4727-b96f-f3dbd52e9b26"
            }
          ]
        },
        {
          "id": "fbed94d7-da22-4af9-b3a9-bbfabccef405",
          "name": "addDelegation",
          "request": {
            "url": "http://www.arin.net/regrws/core/v1/delegation",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This call will add the single nameserver specified in your URL to the Delegation specified in your URL, and return a payload containing that Delegation's information after the nameserver has been added."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6ea7d0d-28d3-442c-8f12-00f9c4737ce8"
            }
          ]
        }
      ]
    }
  ]
}
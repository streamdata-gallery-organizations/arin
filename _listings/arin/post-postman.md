{
  "info": {
    "name": "Delegation API ",
    "_postman_id": "9a4475d8-459c-4bef-92f5-46690c37fd30",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Delegation",
      "item": [
        {
          "id": "c36a7ec0-a38b-4b38-b2b8-b05b7c4e4bd0",
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
              "id": "ddbb2b9e-3442-46d0-895c-c7a729000175"
            }
          ]
        },
        {
          "id": "681a98ec-b9d3-4218-8e58-1d557c4120d0",
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
              "id": "c9d55ee3-bbd4-456b-97a6-4c48d98f0466"
            }
          ]
        },
        {
          "id": "340fcdb3-dc82-469b-b495-ae0da7da69f8",
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
              "id": "ee5e57e7-6c35-4719-acd8-8d2c8baaf2b3"
            }
          ]
        },
        {
          "id": "1567dc78-470d-4bd9-a473-397268cdec91",
          "name": "deleteDelegation",
          "request": {
            "url": "http://www.arin.net/regrws/core/v1/delegation",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "This call will delete the single nameserver specified in your URL from the Delegation specified in your URL, and return a payload containing that Delegation's information after the nameserver has been deleted.  If Reg-RWS returns an error code and/or Error Payload to you when performing this call, refer to the Error Codes section."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4552c876-e8cc-4648-b730-559e6f2683a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "9107c716-dde4-4f31-8eab-393daa21b4ad",
          "name": "Unnammed Endpoint",
          "request": {
            "url": "http://www.arin.net/regrws/core/v1/",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": ""
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fe378e3-40e2-4677-92c2-290d1bac9fd8"
            }
          ]
        }
      ]
    }
  ]
}
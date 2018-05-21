{
  "info": {
    "name": "Delegation API Update Delegation",
    "_postman_id": "b2462c8c-cc7c-429c-8979-44d70efeb39f",
    "description": "This call will modify the details of the Delegation specified in your URL. When making this call, attach a Delegation Payload containing the details of the Delegation you intend to modify. To ensure accuracy, use Get Delegation to get the most current information before making changes. This call returns a payload containing that Delegation's information as it exists after modification.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Delegation",
      "item": [
        {
          "id": "198aebed-381a-4f57-b6a1-5ff02612e882",
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
              "id": "34c9bffe-3ee0-47d1-8590-2d6cb03662e2"
            }
          ]
        },
        {
          "id": "db88a67f-f984-4ea4-b107-9a450b5ba1bb",
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
              "id": "6116ba1a-fc4c-41e3-8a11-5ce3ce807cc3"
            }
          ]
        }
      ]
    }
  ]
}
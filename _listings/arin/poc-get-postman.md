{
  "info": {
    "name": "Point of Contact (POC) API Point of Contact (POC)",
    "_postman_id": "edd39eb0-a1ba-4787-b15c-c49f7d335395",
    "description": "lists the Point of Contact (POC)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Point of Contact",
      "item": [
        {
          "id": "2e95fbed-494b-46e3-b981-92ce9be7e1e4",
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
              "id": "e9d8f65a-e539-455e-9e7b-32a10bec8207"
            }
          ]
        }
      ]
    }
  ]
}
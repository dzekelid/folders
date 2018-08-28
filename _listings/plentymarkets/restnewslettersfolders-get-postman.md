{
  "info": {
    "name": "Plentymarkets List newsletter folders",
    "_postman_id": "21dbd366-b707-4b1b-984d-9fdcde9b2776",
    "description": "List newsletter folders.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "a5edcec8-c20c-4d36-ab9c-7b27e26124b3",
          "name": "getRestNewsletters",
          "request": {
            "url": "http://example.com/rest/newsletters",
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
            "description": "List newsletter entries."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c79c4343-c64c-4a3a-bc79-513e7d34191b"
            }
          ]
        },
        {
          "id": "af1d1ff6-fcb4-4f88-9d23-72760b51958e",
          "name": "getRestNewslettersFolders",
          "request": {
            "url": "http://example.com/rest/newsletters/folders",
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
            "description": "List newsletter folders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "156d0167-258b-4bd0-b3dc-c49346f315a7"
            }
          ]
        }
      ]
    }
  ]
}
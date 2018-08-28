{
  "info": {
    "name": "Microsoft Office 365 Get Folders Folder",
    "_postman_id": "3b51bbdc-ffae-45b4-8572-fd4b7a025de8",
    "description": "You can retrieve information about other folders by using th...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "folders",
      "item": [
        {
          "id": "ff581f85-6fea-413c-9fc7-7b2649039312",
          "name": "getFoldersFolder",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Folders:folder_id"
              ],
              "variable": [
                {
                  "id": "folder_id",
                  "value": "folder_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can retrieve information about other folders by using th"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f74b8521-773a-46b9-aaa2-d52bbfc15ad1"
            }
          ]
        }
      ]
    }
  ]
}
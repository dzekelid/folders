{
  "info": {
    "name": "Microsoft Office 365 Delete Folders Folder",
    "_postman_id": "fd906bb1-9f0e-4a6d-89d5-fb2dd2326cc1",
    "description": "To delete a folder, send a DELETE request to the URL of the ...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "folders",
      "item": [
        {
          "id": "585f8070-f073-4f69-8c40-2440a7fd668c",
          "name": "deleteFoldersFolder",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "To delete a folder, send a DELETE request to the URL of the "
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b94174b-7b3c-49c2-bf60-3176c65d750d"
            }
          ]
        }
      ]
    }
  ]
}
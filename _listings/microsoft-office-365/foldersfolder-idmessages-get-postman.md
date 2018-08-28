{
  "info": {
    "name": "Microsoft Office 365 Get Folders Folder Messages",
    "_postman_id": "2f03be6a-f927-48b5-9efa-0588140955f9",
    "description": "You can request all the emails and meeting requests in a fol...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "folders",
      "item": [
        {
          "id": "9845bcac-6863-4a23-abad-1d2102dd5b71",
          "name": "getFoldersFolderMessages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Folders:folder_id/Messages"
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
            "description": "You can request all the emails and meeting requests in a fol"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6814870-10f8-4d1e-aaad-09fab3b58532"
            }
          ]
        }
      ]
    }
  ]
}
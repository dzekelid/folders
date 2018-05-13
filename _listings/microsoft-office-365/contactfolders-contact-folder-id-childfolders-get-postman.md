{
  "info": {
    "name": "Microsoft Office 365 Get Contact Folders Contact Folder Childfolders",
    "_postman_id": "fb72c58f-ddda-421d-af6c-543a6521b369",
    "description": "All non-default contact folders are stored as children of th...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contactfolders",
      "item": [
        {
          "id": "24159a11-d160-46cc-93d8-8d44f30b5727",
          "name": "getContactfoldersContactFolderChildfolders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "ContactFolders:contact_folder_id/ChildFolders"
              ],
              "variable": [
                {
                  "id": "contact_folder_id",
                  "value": "contact_folder_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "All non-default contact folders are stored as children of th"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfa33d3b-2c6e-462b-8a70-c6c251d1efa3"
            }
          ]
        }
      ]
    }
  ]
}
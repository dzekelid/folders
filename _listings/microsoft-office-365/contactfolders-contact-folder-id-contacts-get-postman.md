{
  "info": {
    "name": "Microsoft Office 365 Get Contact Folders Contact Folder Contacts",
    "_postman_id": "34f2323b-5104-438b-be3f-789c5396e3f1",
    "description": "You can request all contacts (or a filtered set by using the...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contactfolders",
      "item": [
        {
          "id": "b64d1d67-d3df-4771-a0fd-9178dfcb8d61",
          "name": "getContactfoldersContactFolderContacts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "ContactFolders:contact_folder_id/Contacts"
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
            "description": "You can request all contacts (or a filtered set by using the"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1af8590-515d-4f1b-a6af-0264d5e10cb0"
            }
          ]
        }
      ]
    }
  ]
}
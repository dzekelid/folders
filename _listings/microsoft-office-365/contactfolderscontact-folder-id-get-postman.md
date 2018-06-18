{
  "info": {
    "name": "Microsoft Office 365 Get Contact Folders Contact Folder",
    "_postman_id": "25beaae4-7979-44cf-bf82-3678077202c5",
    "description": "You can access the default contact folder by using the const...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contactfolders",
      "item": [
        {
          "id": "ed21fc35-02b4-44ab-8401-c3809e6bd2ae",
          "name": "getContactfoldersContactFolder",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "ContactFolders:contact_folder_id"
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
            "description": "You can access the default contact folder by using the const"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d6f5e8c-b3d7-43dd-8363-f2efb73a88b2"
            }
          ]
        }
      ]
    }
  ]
}
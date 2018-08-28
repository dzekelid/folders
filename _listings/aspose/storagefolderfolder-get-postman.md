{
  "info": {
    "name": "Aspose.Storage API Get Storage Folder Folder",
    "_postman_id": "120900d5-b060-440d-b8ec-fc8c3058ffef",
    "description": "The resource represents customer folder at service file storage.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Storage",
      "item": [
        {
          "id": "3b8d74cb-8a9e-49a2-941e-cf2b68f9427d",
          "name": "getStorageDisc",
          "request": {
            "url": "http://api.aspose.com/v1.1/storage/disc",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents information about users application disc usage (size in bytes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b49b2f45-98d1-4bf7-a888-ddc77ec34c8d"
            }
          ]
        },
        {
          "id": "e4b8de2d-94be-46c9-b7ab-bf23af61a1c0",
          "name": "getStorageExistPath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/exist/:path"
              ],
              "variable": [
                {
                  "id": "path",
                  "value": "path",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The controller checks that the file or folder exists in the service file storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2bd4aae4-278a-439b-affb-2817ac82ca86"
            }
          ]
        },
        {
          "id": "97520970-9291-4c57-b9ff-d6b46474338a",
          "name": "getStorageFilePath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/file/:path"
              ],
              "variable": [
                {
                  "id": "path",
                  "value": "path",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customers file at server file storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23499fc4-e40d-48c0-9a75-a78a0d67263d"
            }
          ]
        },
        {
          "id": "8fe99d23-eaf2-4ea9-8e99-8f0718ad72d9",
          "name": "putStorageFilePath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/file/:path"
              ],
              "variable": [
                {
                  "id": "path",
                  "value": "path",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customers file at server file storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb156953-3c43-4f7a-aed2-cfddd3e5016f"
            }
          ]
        },
        {
          "id": "b8b37f7e-31e5-40ca-aef9-3f80e7029997",
          "name": "postStorageFilePath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/file/:path"
              ],
              "variable": [
                {
                  "id": "path",
                  "value": "path",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customers file at server file storage"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c5b4f3f-75d5-42a2-bcec-638c36d99beb"
            }
          ]
        },
        {
          "id": "9b4f9409-94cd-42d7-84c0-96d5dc994759",
          "name": "deleteStorageFilePath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/file/:path"
              ],
              "variable": [
                {
                  "id": "path",
                  "value": "path",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customers file at server file sto"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ee89753-d727-4613-8d91-b81d02827efc"
            }
          ]
        },
        {
          "id": "570c782d-c4f0-425c-a0ea-aa87bc4369e3",
          "name": "getStorageFolderFolder",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/folder/:folder"
              ],
              "variable": [
                {
                  "id": "folder",
                  "value": "folder",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customer folder at service file storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4d4af8d-a713-4905-8ce2-455cd56e86c2"
            }
          ]
        },
        {
          "id": "de1b0c57-e24e-4692-a9fc-075f1dde9f0a",
          "name": "deleteStorageFolderFolder",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.aspose.com",
              "path": [
                "v1.1",
                "storage/folder/:folder"
              ],
              "variable": [
                {
                  "id": "folder",
                  "value": "folder",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "The resource represents customer folder at service file storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0360e2cc-53b9-4ce4-9fe1-cc91a07e2d94"
            }
          ]
        }
      ]
    }
  ]
}
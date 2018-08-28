{
  "info": {
    "name": "Aspose.Storage API Delete Storage Folder Folder",
    "_postman_id": "460fb7de-a330-45f0-a878-a88ccb0a33a7",
    "description": "The resource represents customer folder at service file storage.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Storage",
      "item": [
        {
          "id": "ed3988d2-74a1-4f1f-aa88-560caae9af40",
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
              "id": "ae0ce9e1-4f24-40ac-9597-c85893091236"
            }
          ]
        },
        {
          "id": "3cad8205-a553-4130-bfc5-cdc6348443b0",
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
              "id": "203ceb47-c3b6-40a1-b095-251b0be3dbfa"
            }
          ]
        },
        {
          "id": "fd29df1f-f97d-414e-91e5-217fa65b0acf",
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
              "id": "58aac252-c169-49c7-af46-e9f8eac88387"
            }
          ]
        },
        {
          "id": "8242ac0d-3399-42ce-a419-f4224a2f19f8",
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
              "id": "6c017032-d094-4efe-822a-83a6406de147"
            }
          ]
        },
        {
          "id": "803c78b7-8329-4cd7-bb7e-46da102b762e",
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
              "id": "ff2bdd39-5618-47c2-ada1-4ba9db10a68f"
            }
          ]
        },
        {
          "id": "3be9ba90-c935-4c3c-b565-a7dae224cb20",
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
              "id": "f4c47a7b-2652-4cf8-88b0-de74f5708190"
            }
          ]
        },
        {
          "id": "65fe3e78-c407-4343-9ba7-5f1876ff5185",
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
              "id": "07c01a73-1fa9-4906-9b5f-0179e2e69f3f"
            }
          ]
        }
      ]
    }
  ]
}
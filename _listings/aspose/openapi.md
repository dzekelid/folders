swagger: "2.0"
x-collection-name: Aspose
x-complete: 1
info:
  title: Aspose
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.aspose.com
basePath: /v1.1
paths:
  /storage/folder/{folder}:
    delete:
      summary: Delete Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: deleteStorageFolderFolder
      x-api-path-slug: storagefolderfolder-delete
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder
    get:
      summary: Get Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: getStorageFolderFolder
      x-api-path-slug: storagefolderfolder-get
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder
    post:
      summary: Post Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: postStorageFolderFolder
      x-api-path-slug: storagefolderfolder-post
      parameters:
      - in: query
        name: dest
        description: Moves (renames) the file to NewFile
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder
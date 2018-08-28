---
swagger: "2.0"
x-collection-name: Aspose
x-complete: 0
info:
  title: Aspose.Storage API Get Storage Folder Folder
  description: The resource represents customer folder at service file storage.
  termsOfService: http://www.aspose.com/corporate/legal/terms-of-use.aspx
  version: v1.1
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
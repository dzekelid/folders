---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox
  description: the-dropbox-api-allows-you-to-build-the-power-of-dropbox-directly-into-your-app-
  version: "1"
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /shared_folders:
    get:
      summary: Shared Folders
      description: /shared_folders
      operationId: shared-folders
      x-api-path-slug: shared-folders-get
      parameters:
      - in: query
        name: id
        description: The ID of a specific shared folder
      responses:
        200:
          description: OK
      tags:
      - Shared
      - Folders
---
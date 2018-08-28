---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Datastore API Create Folder
  description: /fileops/create_folder
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
  /fileops/create_folder:
    post:
      summary: Create Folder
      description: /fileops/create_folder
      operationId: fileopscreate-folder
      x-api-path-slug: fileopscreate-folder-post
      parameters:
      - in: query
        name: locale
        description: The metadata returned will have its size field translated based
          on the given locale
      - in: query
        name: path
        description: The path to the new folder to create relative to root
      - in: query
        name: root
        description: The root relative to which path is specified
      responses:
        200:
          description: OK
      tags:
      - Fileops
      - Create
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
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Notify Appendix API v1
  description: the-dropbox-notify--is-a-part-of-dropbox-core-ap-with-a-separate-endpoint-for-notification-call-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api-notify.dropbox.com
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
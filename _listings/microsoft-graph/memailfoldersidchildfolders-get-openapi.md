---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Child Folders
  description: List childFolders Get the folder collection under the specified folder.
    You can use the .../me/MailFolders shortcut to get the top-level folder collection
    and navigate to another folder.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/contactFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get a collection of child folders under the specified
        contact folder.
      operationId: ListChildFolders
      x-api-path-slug: mecontactfoldersidchildfolders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Child
      - Folders
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get a collection of child folders under the specified
        contact folder.
      operationId: ListChildFolders
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfolders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Child
      - Folders
  /me/mailFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get the folder collection under the specified
        folder. You can use the .../me/MailFolders shortcut to get the top-level folder
        collection and navigate to another folder.
      operationId: ListChildFolders
      x-api-path-slug: memailfoldersidchildfolders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Child
      - Folders
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
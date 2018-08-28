---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List all recipients of a folder
  description: Lists all recipients of a folder. The ID of the folder must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/newsletters/folders:
    delete:
      summary: Delete folders
      description: Delete folders.
      operationId: deleteRestNewslettersFolders
      x-api-path-slug: restnewslettersfolders-delete
      responses:
        200:
          description: OK
      tags:
      - Folders
    get:
      summary: List newsletter folders
      description: List newsletter folders.
      operationId: getRestNewslettersFolders
      x-api-path-slug: restnewslettersfolders-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Newsletter
      - Folders
    post:
      summary: Create a folder
      description: Create a folder.
      operationId: postRestNewslettersFolders
      x-api-path-slug: restnewslettersfolders-post
      parameters:
      - in: body
        name: /rest/newsletters/folders
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: The ID of the newsletter folder
      - in: query
        name: isDeletable
        description: Flag that indicates if the newsletter folder can be deleted
      - in: query
        name: isSelectable
        description: Flag that indicates if the newsletter folder can be selected
          by customers in the online store
      - in: query
        name: name
        description: The name of the newsletter folder
      - in: query
        name: position
        description: The position of the newsletter folder
      responses:
        200:
          description: OK
      tags:
      - Folder
  /rest/newsletters/folders/{folderId}:
    delete:
      summary: Delete a folder
      description: Deletes a folder. The ID of the folder must be specified.
      operationId: deleteRestNewslettersFoldersFolder
      x-api-path-slug: restnewslettersfoldersfolderid-delete
      parameters:
      - in: path
        name: folderId
      responses:
        200:
          description: OK
      tags:
      - Folder
    get:
      summary: List details of a folder
      description: Lists details of a folder. The ID of the folder must be specified.
      operationId: getRestNewslettersFoldersFolder
      x-api-path-slug: restnewslettersfoldersfolderid-get
      parameters:
      - in: path
        name: folderId
      responses:
        200:
          description: OK
      tags:
      - List
      - Details
      - Of
      - Folder
    put:
      summary: Update a folder
      description: Updates a folder. The ID of the folder must be specified.
      operationId: putRestNewslettersFoldersFolder
      x-api-path-slug: restnewslettersfoldersfolderid-put
      parameters:
      - in: query
        name: clientIds
        description: The IDs of the clients (stores)
      - in: path
        name: folderId
      - in: query
        name: isDeletable
        description: Flag that indicates if the newsletter folder can be deleted
      - in: query
        name: isSelectable
        description: Flag that indicates if the newsletter folder can be selected
          by customers in the online store
      - in: query
        name: name
        description: The name of the newsletter folder
      - in: query
        name: position
        description: The position of the newsletter folder
      responses:
        200:
          description: OK
      tags:
      - Folder
  /rest/newsletters/folders/{folderId}/recipients:
    get:
      summary: List all recipients of a folder
      description: Lists all recipients of a folder. The ID of the folder must be
        specified.
      operationId: getRestNewslettersFoldersFolderRecipients
      x-api-path-slug: restnewslettersfoldersfolderidrecipients-get
      parameters:
      - in: path
        name: folderId
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Recipients
      - Of
      - Folder
  /rest/newsletters/recipients:
    get:
      summary: List recipients of a folder
      description: List recipients of a folder.
      operationId: getRestNewslettersRecipients
      x-api-path-slug: restnewslettersrecipients-get
      parameters:
      - in: query
        name: email
        description: Filter that restricts the search result to the email address
          of the recipient
      - in: query
        name: folderId
        description: Filter that restricts the search result to the folder ID
      - in: query
        name: recipientId
        description: Filter that restricts the search result to the recipient ID
      responses:
        200:
          description: OK
      tags:
      - List
      - Recipients
      - Of
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
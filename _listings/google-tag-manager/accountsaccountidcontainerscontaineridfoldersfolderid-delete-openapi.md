---
swagger: "2.0"
x-collection-name: Google Tag Manager
x-complete: 0
info:
  title: Google Tag Manager API Delete GTM Folder
  description: Deletes a GTM Folder.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /tagmanager/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/containers/{containerId}/folders:
    get:
      summary: Get GTM Folders
      description: Lists all GTM Folders of a Container.
      operationId: tagmanager.accounts.containers.folders.list
      x-api-path-slug: accountsaccountidcontainerscontaineridfolders-get
      parameters:
      - in: path
        name: accountId
        description: The GTM Account ID
      - in: path
        name: containerId
        description: The GTM Container ID
      responses:
        200:
          description: OK
      tags:
      - GTM Folder
    post:
      summary: Create GTM Folder
      description: Creates a GTM Folder.
      operationId: tagmanager.accounts.containers.folders.create
      x-api-path-slug: accountsaccountidcontainerscontaineridfolders-post
      parameters:
      - in: path
        name: accountId
        description: The GTM Account ID
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: containerId
        description: The GTM Container ID
      responses:
        200:
          description: OK
      tags:
      - GTM Folder
  /accounts/{accountId}/containers/{containerId}/folders/{folderId}:
    delete:
      summary: Delete GTM Folder
      description: Deletes a GTM Folder.
      operationId: tagmanager.accounts.containers.folders.delete
      x-api-path-slug: accountsaccountidcontainerscontaineridfoldersfolderid-delete
      parameters:
      - in: path
        name: accountId
        description: The GTM Account ID
      - in: path
        name: containerId
        description: The GTM Container ID
      - in: path
        name: folderId
        description: The GTM Folder ID
      responses:
        200:
          description: OK
      tags:
      - GTM Folder
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
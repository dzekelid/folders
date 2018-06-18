---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Delete Folder
  description: Used to delete a folder. A recursive parameter must be included in
    order to delete folders that have items inside of them. An optional If-Match header
    can be included to ensure that client only deletes the folder if it knows about
    the latest version.
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /folders:
    post:
      summary: Create Folder
      description: Used to create a new empty folder. The new folder will be created
        inside of the specified parent folder
      operationId: createFolder
      x-api-path-slug: folders-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
  /folders/{FOLDER_ID}:
    get:
      summary: Get Folder's Info
      description: "Retrieves the full metadata about a folder, including information
        about when it was last updated as well as the files and folders contained
        in it. The root folder of a Box account is always represented by the id \u201C0\u201D."
      operationId: getFolder
      x-api-path-slug: foldersfolder-id-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
    put:
      summary: Update Folder, Create Shared Link, Create or Delete
      description: "Used to update information about the folder. To move a folder,
        update the ID of its parent. To enable an email address that can be used to
        upload files to this folder, update the folder_upload_email attribute. An
        optional If-Match header can be included to ensure that client only updates
        the folder if it knows about the latest version.\n\nUsed to create a shared
        link for this particular folder. Please see here for more information on the
        permissions available for shared links. In order to get default shared link
        status, set it to an empty access level, i.e. {\"shared_link\": {}}. In order
        to disable a shared link, send this same type of PUT request with the value
        of shared_link set to null, i.e. {\"shared_link\": null}\n\nTo add or remove
        an item from a collection, you do a PUT on that item and change the list of
        collections it belongs to. Philosophically, this is similar to the way \u201Cmove\u201D
        operations work on files and folders: you do a PUT on the item and change
        its parent. It\u2019s the same idea with collections, except you\u2019re changing
        which collection(s) the item belongs to instead of the folder it belongs to.
        Currently the only collection available is the favorites collection, and you\u2019ll
        need to know it\u2019s ID for the user that is making the API call, since
        every user has a different favorites collection_id.\nThe Add/Remove API handling
        will check all ids passed in before performing any add/removal operations.
        If any collection ids are malformed or do not exist in the user\u2019s account,
        the API call will throw a 400. Only if all of the collection ids are valid
        will the adds and removals be carried out."
      operationId: updateFolder
      x-api-path-slug: foldersfolder-id-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: path
        name: FOLDER_ID
      - in: header
        name: If-Match
        description: This is in the etag field of the folder object
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
    delete:
      summary: Delete Folder
      description: Used to delete a folder. A recursive parameter must be included
        in order to delete folders that have items inside of them. An optional If-Match
        header can be included to ensure that client only deletes the folder if it
        knows about the latest version.
      operationId: deleteFolder
      x-api-path-slug: foldersfolder-id-delete
      parameters:
      - in: path
        name: FOLDER_ID
      - in: header
        name: If-Match
        description: This is in the etag field of the folder object
      - in: query
        name: recursive
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
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
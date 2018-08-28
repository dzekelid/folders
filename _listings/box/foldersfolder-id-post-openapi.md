---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Restore Folder
  description: Restores an item that has been moved to the trash. Default behavior
    is to restore the item to the folder it was in before it was moved to the trash.
    If that parent folder no longer exists or if there is now an item with the same
    name in that parent folder, the new parent folder and/or new name will need to
    be included in the request.
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
      description: Retrieves the full metadata about a folder, including information
        about when it was last updated as well as the files and folders contained
        in it. The root folder of a Box account is always represented by the id ???0???.
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
      description: |-
        Used to update information about the folder. To move a folder, update the ID of its parent. To enable an email address that can be used to upload files to this folder, update the folder_upload_email attribute. An optional If-Match header can be included to ensure that client only updates the folder if it knows about the latest version.

        Used to create a shared link for this particular folder. Please see here for more information on the permissions available for shared links. In order to get default shared link status, set it to an empty access level, i.e. {"shared_link": {}}. In order to disable a shared link, send this same type of PUT request with the value of shared_link set to null, i.e. {"shared_link": null}

        To add or remove an item from a collection, you do a PUT on that item and change the list of collections it belongs to. Philosophically, this is similar to the way ???move??? operations work on files and folders: you do a PUT on the item and change its parent. It???s the same idea with collections, except you???re changing which collection(s) the item belongs to instead of the folder it belongs to. Currently the only collection available is the favorites collection, and you???ll need to know it???s ID for the user that is making the API call, since every user has a different favorites collection_id.
        The Add/Remove API handling will check all ids passed in before performing any add/removal operations. If any collection ids are malformed or do not exist in the user???s account, the API call will throw a 400. Only if all of the collection ids are valid will the adds and removals be carried out.
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
        description: This is in the ???etag??? field of the folder object
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
        description: This is in the ???etag??? field of the folder object
      - in: query
        name: recursive
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
    post:
      summary: Restore Folder
      description: Restores an item that has been moved to the trash. Default behavior
        is to restore the item to the folder it was in before it was moved to the
        trash. If that parent folder no longer exists or if there is now an item with
        the same name in that parent folder, the new parent folder and/or new name
        will need to be included in the request.
      operationId: restoreTrashedFolder
      x-api-path-slug: foldersfolder-id-post
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
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
  /folders/{FOLDER_ID}/items:
    get:
      summary: Get Folder???s Items
      description: Retrieves the files and/or folders contained within this folder
        without any other metadata about the folder. Any attribute in the full files
        or folders objects can be passed in with the fields parameter to get specific
        attributes, and only those specific attributes back; otherwise, the mini format
        is returned for each item by default. Multiple attributes can be passed in
        separated by commas e.g. fields=name,created_at. Paginated results can be
        retrieved using the limit and offset parameters.
      operationId: getFolderItems
      x-api-path-slug: foldersfolder-iditems-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: path
        name: FOLDER_ID
      - in: query
        name: limit
        description: The maximum number of items to return in a page
      - in: query
        name: offset
        description: The offset at which to begin the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Items
  /folders/{FOLDER_ID}/copy:
    post:
      summary: Copy Folder
      description: Used to create a copy of a folder in another folder. The original
        version of the folder will not be altered.
      operationId: copyFolder
      x-api-path-slug: foldersfolder-idcopy-post
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
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Copy
  /folders/{FOLDER_ID}/collaborations:
    get:
      summary: Get Folder Collaborations
      description: Use this to get a list of all the collaborations on a folder i.e.
        all of the users that have access to that folder.
      operationId: getFolderCollaborations
      x-api-path-slug: foldersfolder-idcollaborations-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: path
        name: FOLDER_ID
      - in: query
        name: limit
        description: The maximum number of items to return in a page
      - in: query
        name: offset
        description: The item at which to begin the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Collaborations
  /folders/{FOLDER_ID}/trash:
    get:
      summary: Get Trashed Folder
      description: Retrieves an folder that has been moved to the trash.
      operationId: getTrashedFolder
      x-api-path-slug: foldersfolder-idtrash-get
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
      - ""
      - Trash
    delete:
      summary: Permanently Delete
      description: Permanently deletes an folder that is in the trash. The item will
        no longer exist in Box. This action cannot be undone.
      operationId: deleteTrashedFolder
      x-api-path-slug: foldersfolder-idtrash-delete
      parameters:
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Trash
  /folders/trash/items:
    get:
      summary: Get Trashed Items
      description: Retrieves the files and/or folders that have been moved to the
        trash. Any attribute in the full files or folders objects can be passed in
        with the fields parameter to get specific attributes, and only those specific
        attributes back; otherwise, the mini format is returned for each item by default.
        Multiple attributes can be passed in separated by commas e.g. fields=name,created_at.
        Paginated results can be retrieved using the limit and offset parameters.
      operationId: getTrashedItems
      x-api-path-slug: folderstrashitems-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: offset
        description: The item at which to begin the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Trash
      - Items
  /folders/{FOLDER_ID}/watermark:
    get:
      summary: Get Watermark on Folder
      description: Used to retrieve the watermark for a corresponding Box folder.
      operationId: getFolderWatermark
      x-api-path-slug: foldersfolder-idwatermark-get
      parameters:
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Watermark
    put:
      summary: Apply Watermark on Folder
      description: Used to apply or update the watermark for a corresponding Box folder.
        The endpoints accepts a JSON body describing the watermark to apply.
      operationId: updateFolderWatermark
      x-api-path-slug: foldersfolder-idwatermark-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Watermark
    delete:
      summary: Remove Watermark on Folder
      description: Used to remove the watermark for a corresponding Box Folder.
      operationId: deleteFolderWatermark
      x-api-path-slug: foldersfolder-idwatermark-delete
      parameters:
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Watermark
  /folders/{FOLDER_ID}/metadata:
    get:
      summary: Get All Metadata on Folder
      description: Used to retrieve all metadata associated with a given folder
      operationId: getAllFolderMetadata
      x-api-path-slug: foldersfolder-idmetadata-get
      parameters:
      - in: path
        name: FOLDER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Metadata
  /folders/{FOLDER_ID}/metadata/{SCOPE}/{TEMPLATE}:
    post:
      summary: Create Metadata on Folder
      description: Used to create the metadata template instance for a corresponding
        Box folder. When creating metadata, only values that adhere to the metadata
        template schema will be accepted.
      operationId: createFolderMetadata
      x-api-path-slug: foldersfolder-idmetadatascopetemplate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FOLDER_ID
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Metadata
      - Scope
      - Template
    get:
      summary: Get Metadata on Folder
      description: Used to retrieve the metadata template instance for a corresponding
        Box folder.
      operationId: getFolderMetadata
      x-api-path-slug: foldersfolder-idmetadatascopetemplate-get
      parameters:
      - in: path
        name: FOLDER_ID
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Metadata
      - Scope
      - Template
    put:
      summary: Update Metadata on Folder
      description: Used to update the template instance. Updates can be either add,
        replace, remove , or test. The template instance can only be updated if the
        template instance already exists. When editing metadata, only values that
        adhere to the metadata template schema will be accepted.
      operationId: updateFolderMetadata
      x-api-path-slug: foldersfolder-idmetadatascopetemplate-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: FOLDER_ID
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Metadata
      - Scope
      - Template
    delete:
      summary: Delete Metadata on Folder
      description: Used to delete the template instance. To delete custom key:value
        pairs within a template instance, you should refer to the updating metadata
        section.
      operationId: deleteFolderMetadata
      x-api-path-slug: foldersfolder-idmetadatascopetemplate-delete
      parameters:
      - in: path
        name: FOLDER_ID
      - in: path
        name: SCOPE
      - in: path
        name: TEMPLATE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Folders
      - Folder
      - ""
      - Metadata
      - Scope
      - Template
  /users/{USER_ID}/folders/{FOLDER_ID}:
    put:
      summary: Move User's Folder
      description: Moves all of the owned content from within one user???s folder
        into a new folder in another user???s account. You can move folders across
        users as long as the you have administrative permissions and the ???source???
        user owns the folders. To move everything from the root folder, use ???0???
        which always represents the root folder of a Box account.
      operationId: updateUserFolder
      x-api-path-slug: usersuser-idfoldersfolder-id-put
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
      - in: query
        name: notify
      - in: path
        name: USER_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Users
      - User
      - ""
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
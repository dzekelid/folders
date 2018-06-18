---
swagger: "2.0"
x-collection-name: AWS WorkDocs
x-complete: 0
info:
  title: AWS WorkDocs API Get Folder
  version: 1.0.0
  description: Retrieves the metadata of the specified folder.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateFolder:
    get:
      summary: Create Folder
      description: Creates a folder with the specified name and parent folder.
      operationId: createFolder
      x-api-path-slug: actioncreatefolder-get
      parameters:
      - in: query
        name: Name
        description: The name of the new folder
        type: string
      - in: query
        name: ParentFolderId
        description: The ID of the parent folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=DeleteFolder:
    get:
      summary: Delete Folder
      description: Permanently deletes the specified folder and its contents.
      operationId: deleteFolder
      x-api-path-slug: actiondeletefolder-get
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=DeleteFolderContents:
    get:
      summary: Delete Folder Contents
      description: Deletes the contents of the specified folder.
      operationId: deleteFolderContents
      x-api-path-slug: actiondeletefoldercontents-get
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=DescribeFolderContents:
    get:
      summary: Describe Folder Contents
      description: Describes the contents of the specified folder, including its documents
        and sub-folders.
      operationId: describeFolderContents
      x-api-path-slug: actiondescribefoldercontents-get
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      - in: query
        name: Include
        description: The contents to include
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Order
        description: The order for the contents of the folder
        type: string
      - in: query
        name: Sort
        description: The sorting criteria
        type: string
      - in: query
        name: Type
        description: The type of items
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=GetFolder:
    get:
      summary: Get Folder
      description: Retrieves the metadata of the specified folder.
      operationId: getFolder
      x-api-path-slug: actiongetfolder-get
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      responses:
        200:
          description: OK
      tags:
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
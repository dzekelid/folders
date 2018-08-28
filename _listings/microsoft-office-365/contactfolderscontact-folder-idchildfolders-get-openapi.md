---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Get Contact Folders Contact Folder Childfolders
  description: All non-default contact folders are stored as children of th...
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Folders{folder_id}:
    get:
      summary: Get Folders Folder
      description: You can retrieve information about other folders by using th...
      operationId: getFoldersFolder
      x-api-path-slug: foldersfolder-id-get
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
    post:
      summary: Add Folders Folder
      description: You can create a folder by sending a POST request with a JSO...
      operationId: postFoldersFolder
      x-api-path-slug: foldersfolder-id-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
    delete:
      summary: Delete Folders Folder
      description: To delete a folder, send a DELETE request to the URL of the ...
      operationId: deleteFoldersFolder
      x-api-path-slug: foldersfolder-id-delete
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
    patch:
      summary: Patch Folders Folder
      description: You can update a folder by sending a PATCH request with a JS...
      operationId: patchFoldersFolder
      x-api-path-slug: foldersfolder-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
    parameters:
      summary: Parameters Folders Folder
      description: Parameters folders folder
      operationId: parametersFoldersFolder
      x-api-path-slug: foldersfolder-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
  /Folders{folder_id}/Messages:
    get:
      summary: Get Folders Folder Messages
      description: You can request all the emails and meeting requests in a fol...
      operationId: getFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-get
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
    post:
      summary: Add Folders Folder Messages
      description: You can create an email by sending a POST request with a JSO...
      operationId: postFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: MessageDisposition
        description: When sending a POST request to create an email, there is an optional
          MessageDisposition query parameter that controls what happens to the message
          as it is created
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
    parameters:
      summary: Parameters Folders Folder Messages
      description: Parameters folders folder  messages
      operationId: parametersFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-parameters
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
  /ContactFolders{contact_folder_id}:
    get:
      summary: Get Contact Folders Contact Folder
      description: You can access the default contact folder by using the const...
      operationId: getContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
    parameters:
      summary: Parameters Contact Folders Contact Folder
      description: Parameters contactfolders contact folder
      operationId: parametersContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
  /ContactFolders{contact_folder_id}/ChildFolders:
    get:
      summary: Get Contact Folders Contact Folder Childfolders
      description: All non-default contact folders are stored as children of th...
      operationId: getContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
    parameters:
      summary: Parameters Contact Folders Contact Folder Childfolders
      description: Parameters contactfolders contact folder  childfolders
      operationId: parametersContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
  /ContactFolders{contact_folder_id}/Contacts:
    get:
      summary: Get Contact Folders Contact Folder Contacts
      description: You can request all contacts (or a filtered set by using the...
      operationId: getContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    post:
      summary: Add Contact Folders Contact Folder Contacts
      description: You can create a contact by sending a POST request with a JS...
      operationId: postContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    parameters:
      summary: Parameters Contact Folders Contact Folder Contacts
      description: Parameters contactfolders contact folder  contacts
      operationId: parametersContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
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
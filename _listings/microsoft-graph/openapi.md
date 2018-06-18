---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /users/{id | userPrincipalName}/mailFolders/{id}/childFolders:
    get:
      summary: List Child Folders
      description: List childFolders Get the folder collection under the specified
        folder. You can use the .../me/MailFolders shortcut to get the top-level folder
        collection and navigate to another folder.
      operationId: ListChildFolders
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfolders-get
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
  /users/{id | userPrincipalName}/contactFolders:
    get:
      summary: List Contact Folders
      description: List contactFolders Get the contact folder collection in the default
        Contacts folder of the signed-in user.
      operationId: ListContactFolders
      x-api-path-slug: usersid--userprincipalnamecontactfolders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Folders
  /users/{id | userPrincipalName}/mailFolders:
    get:
      summary: List Mail Folders
      description: List mailFolders Get the mail folder collection under the root
        folder of the signed-in user.
      operationId: ListMailFolders
      x-api-path-slug: usersid--userprincipalnamemailfolders-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Mail
      - Folders
---
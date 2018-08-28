---
swagger: "2.0"
x-collection-name: SugarSync
x-complete: 0
info:
  title: Sugar Sync  API Deleting a Folder
  description: An application can permanantly delete a folder by issuing an HTTP DELETE
    request to the URL of thenfolder resource.nIts a good idea to precede DELETE requests
    like this with a caution note in your applications user interface.n
  version: "1"
host: api.sugarsync.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /folder:
    get:
      summary: Retrieving Folder Information
      description: To retrieve information about a folder, an application submits
        an HTTP GET request to then          folder resource that represents the folder.
      operationId: retrieving-folder-information
      x-api-path-slug: folder-get
      responses:
        200:
          description: OK
      tags:
      - Folder
  /folder/:
    delete:
      summary: Deleting a Folder
      description: An application can permanantly delete a folder by issuing an HTTP
        DELETE request to the URL of thenfolder resource.nIts a good idea to precede
        DELETE requests like this with a caution note in your applications user interface.n
      operationId: deleting-a-folder
      x-api-path-slug: folder-delete
      responses:
        200:
          description: OK
      tags:
      - Folder
    get:
      summary: Retrieving Folder Contents
      description: To retrieve the contents of a folder, an application submits an
        HTTP GET request to the URLn          that represents the folder contents.
      operationId: retrieving-folder-contents
      x-api-path-slug: folder-get
      parameters:
      - in: query
        name: max
        description: Positive integer
      - in: query
        name: order
        description: name, last_modified, size, or extension
      - in: query
        name: start
        description: 0 or positive integer
      - in: query
        name: type
        description: folder or file
      responses:
        200:
          description: OK
      tags:
      - Folder
    post:
      summary: Creating a Folder
      description: An application can create a folder within another folder by issuing
        an HTTP POST request to the URL ofnthe containing folder resource.nIn addition,
        the application needs to provide as input, XML that identifies the display
        name of the folder to be created.nNote that an application can create a folder
        only within another folder, and not directly in a workspace.
      operationId: creating-a-folder
      x-api-path-slug: folder-post
      parameters:
      - in: header
        name: Authorization
        description: The access token
      - in: header
        name: Content-Length
        description: The length of the request body
      - in: header
        name: Content-Type
        description: The content type and character encoding of the response
      - in: header
        name: Host
        description: The domain name of the server
      - in: header
        name: User-Agent
        description: The client application implementing the network protocol for
          communication between          the client and server
      responses:
        200:
          description: OK
      tags:
      - Folder
    put:
      summary: Updating Folder Information
      description: An application can update various attributes of a folder by issuing
        an HTTP PUT request to the URL thatnrepresents the folder resource. In addition,
        the app needs to provide as input, XML that identifies the new attribute values
        for the folder. Upon receiving the PUT request, the SugarSync service examines
        the input and updates any of the attributes that have been modified.
      operationId: updating-folder-information
      x-api-path-slug: folder-put
      parameters:
      - in: header
        name: Authorization
        description: The access token
      - in: header
        name: Content-Length
        description: The length of the request body
      - in: header
        name: Content-Type
        description: The content type and character encoding of the response
      - in: header
        name: Host
        description: The domain name of the server
      - in: header
        name: User-Agent
        description: The client application implementing the network protocol for
          communication between          the client and server
      responses:
        200:
          description: OK
      tags:
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
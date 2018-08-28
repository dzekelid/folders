swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/folders:
    get:
      summary: List all folders
      description: List all folders.
      operationId: list-all-folders
      x-api-path-slug: coursescourse-idfolders-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Folders
    post:
      summary: Create folder
      description: Create folder.
      operationId: create-folder
      x-api-path-slug: coursescourse-idfolders-post
      parameters:
      - in: query
        name: hidden
        description: Flag the folder as hidden
      - in: query
        name: locked
        description: Flag the folder as locked
      - in: query
        name: lock_at
        description: The datetime to lock the folder at
      - in: query
        name: name
        description: The name of the folder
      - in: query
        name: parent_folder_id
        description: The id of the folder to store the file in
      - in: query
        name: parent_folder_path
        description: The path of the folder to store the new folder in
      - in: query
        name: position
        description: Set an explicit sort position for the folder
      - in: query
        name: unlock_at
        description: The datetime to unlock the folder at
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Folders
  /courses/{course_id}/folders/by_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: coursescourse-idfoldersby-path-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Folders
      - By
      - Path
  /courses/{course_id}/folders/by_path/*full_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: coursescourse-idfoldersby-pathfull-path-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Folders
      - By
      - Path
      - '*full'
      - Path
  /courses/{course_id}/folders/id:
    get:
      summary: Get folder
      description: Get folder.
      operationId: get-folder
      x-api-path-slug: coursescourse-idfoldersid-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Folders
      - Id
  /groups/{group_id}/folders:
    get:
      summary: List all folders
      description: List all folders.
      operationId: list-all-folders
      x-api-path-slug: groupsgroup-idfolders-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Folders
    post:
      summary: Create folder
      description: Create folder.
      operationId: create-folder
      x-api-path-slug: groupsgroup-idfolders-post
      parameters:
      - in: query
        name: hidden
        description: Flag the folder as hidden
      - in: query
        name: locked
        description: Flag the folder as locked
      - in: query
        name: lock_at
        description: The datetime to lock the folder at
      - in: query
        name: name
        description: The name of the folder
      - in: query
        name: parent_folder_id
        description: The id of the folder to store the file in
      - in: query
        name: parent_folder_path
        description: The path of the folder to store the new folder in
      - in: query
        name: position
        description: Set an explicit sort position for the folder
      - in: query
        name: unlock_at
        description: The datetime to unlock the folder at
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Folders
  /groups/{group_id}/folders/by_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: groupsgroup-idfoldersby-path-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Folders
      - By
      - Path
  /groups/{group_id}/folders/by_path/*full_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: groupsgroup-idfoldersby-pathfull-path-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Folders
      - By
      - Path
      - '*full'
      - Path
  /groups/{group_id}/folders/id:
    get:
      summary: Get folder
      description: Get folder.
      operationId: get-folder
      x-api-path-slug: groupsgroup-idfoldersid-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Folders
      - Id
  /users/{user_id}/folders:
    get:
      summary: List all folders
      description: List all folders.
      operationId: list-all-folders
      x-api-path-slug: usersuser-idfolders-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Folders
    post:
      summary: Create folder
      description: Create folder.
      operationId: create-folder
      x-api-path-slug: usersuser-idfolders-post
      parameters:
      - in: query
        name: hidden
        description: Flag the folder as hidden
      - in: query
        name: locked
        description: Flag the folder as locked
      - in: query
        name: lock_at
        description: The datetime to lock the folder at
      - in: query
        name: name
        description: The name of the folder
      - in: query
        name: parent_folder_id
        description: The id of the folder to store the file in
      - in: query
        name: parent_folder_path
        description: The path of the folder to store the new folder in
      - in: query
        name: position
        description: Set an explicit sort position for the folder
      - in: query
        name: unlock_at
        description: The datetime to unlock the folder at
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Folders
  /users/{user_id}/folders/by_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: usersuser-idfoldersby-path-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Folders
      - By
      - Path
  /users/{user_id}/folders/by_path/*full_path:
    get:
      summary: Resolve path
      description: Resolve path.
      operationId: resolve-path
      x-api-path-slug: usersuser-idfoldersby-pathfull-path-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Folders
      - By
      - Path
      - '*full'
      - Path
  /users/{user_id}/folders/id:
    get:
      summary: Get folder
      description: Get folder.
      operationId: get-folder
      x-api-path-slug: usersuser-idfoldersid-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Folders
      - Id
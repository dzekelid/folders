---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Customer APIs Uploads a file to the temp folder
  description: Uploads a file to the temp folder for an organization.
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /documents/organizations/{organizationId}/TEMP/upload:
    post:
      summary: Uploads a file to the temp folder
      description: Uploads a file to the temp folder for an organization.
      operationId: uploads-a-file-to-the-temp-folder-for-an-organization
      x-api-path-slug: documentsorganizationsorganizationidtempupload-post
      parameters:
      - in: formData
        name: fileUpload
        description: A file to be uploaded
      - in: path
        name: organizationId
        description: The ID of an organization
      responses:
        200:
          description: Successful response
      tags:
      - Uploads
      - File
      - To
      - Temp
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
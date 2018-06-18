---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Core Returns metadata about a specific shared folder.
  description: |-
    Returns metadata about a specific shared folder.

    This API call requires Full Dropbox or File type [permissions](https://www.dropbox.com/developers/reference/devguide#app-permissions).

    Note that `same_team` is only present if the linked account is a member of a Dropbox for Business team,
    and `member_id` is only present when this endpoint is called by a Dropbox for Business app and the user
    is on that team.

    The `membership` field only contains users who have joined the shared folder and does not include users who
    have been invited but have not accepted. When the `active` field is `false`, it means that a user has left
    a shared folder (but may still rejoin).
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /shared_folders:
    get:
      summary: Returns a list of all shared folders.
      description: |-
        Returns a list of all shared folders the authenticated user has access to.

        This API call requires Full Dropbox or File type [permissions](https://www.dropbox.com/developers/reference/devguide#app-permissions).

        Note that `same_team` is only present if the linked account is a member of a Dropbox for Business team,
        and `member_id` is only present when this endpoint is called by a Dropbox for Business app and the user
        is on that team.

        The `membership` field only contains users who have joined the shared folder and does not include users who
        have been invited but have not accepted. When the `active` field is `false`, it means that a user has left
        a shared folder (but may still rejoin).
      operationId: returns-a-list-of-all-shared-folders-the-authenticated-user-has-access-tothis-api-call-requires-full
      x-api-path-slug: shared-folders-get
      parameters:
      - in: query
        name: include_membership
        description: If `true`, include a list of members and a list of groups for
          the shared folder
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Shared_folders
  /shared_folders/{shared_folder_id}:
    get:
      summary: Returns metadata about a specific shared folder.
      description: |-
        Returns metadata about a specific shared folder.

        This API call requires Full Dropbox or File type [permissions](https://www.dropbox.com/developers/reference/devguide#app-permissions).

        Note that `same_team` is only present if the linked account is a member of a Dropbox for Business team,
        and `member_id` is only present when this endpoint is called by a Dropbox for Business app and the user
        is on that team.

        The `membership` field only contains users who have joined the shared folder and does not include users who
        have been invited but have not accepted. When the `active` field is `false`, it means that a user has left
        a shared folder (but may still rejoin).
      operationId: returns-metadata-about-a-specific-shared-folderthis-api-call-requires-full-dropbox-or-file-type-perm
      x-api-path-slug: shared-foldersshared-folder-id-get
      parameters:
      - in: query
        name: include_membership
        description: If `true`, include a list of members and a list of groups for
          the shared folder
      - in: path
        name: shared_folder_id
        description: The ID of a specific shared folder
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Shared_folders
      - Shared_folder_id
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
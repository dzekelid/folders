---
name: Box
x-slug: box
description: Box is changing how you manage content across your business from simple
  file sharing to building custom apps.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
x-kinRank: "9"
x-alexaRank: "445"
tags: Folders
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/apis.md
specificationVersion: "0.14"
apis:
- name: Box Create Folder
  x-api-slug: box
  description: Used to create a new empty folder. The new folder will be created inside
    of the specified parent folder
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders
  tags: Documents,Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/folders-post-openapi.md
- name: Box Get Folder's Info
  x-api-slug: box
  description: "Retrieves the full metadata about a folder, including information
    about when it was last updated as well as the files and folders contained in it.
    The root folder of a Box account is always represented by the id \u201C0\u201D."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}
  tags: Documents,Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-get-openapi.md
- name: Box Update Folder, Create Shared Link, Create or Delete
  x-api-slug: box
  description: "Used to update information about the folder. To move a folder, update
    the ID of its parent. To enable an email address that can be used to upload files
    to this folder, update the folder_upload_email attribute. An optional If-Match
    header can be included to ensure that client only updates the folder if it knows
    about the latest version.\n\nUsed to create a shared link for this particular
    folder. Please see here for more information on the permissions available for
    shared links. In order to get default shared link status, set it to an empty access
    level, i.e. {\"shared_link\": {}}. In order to disable a shared link, send this
    same type of PUT request with the value of shared_link set to null, i.e. {\"shared_link\":
    null}\n\nTo add or remove an item from a collection, you do a PUT on that item
    and change the list of collections it belongs to. Philosophically, this is similar
    to the way \u201Cmove\u201D operations work on files and folders: you do a PUT
    on the item and change its parent. It\u2019s the same idea with collections, except
    you\u2019re changing which collection(s) the item belongs to instead of the folder
    it belongs to. Currently the only collection available is the favorites collection,
    and you\u2019ll need to know it\u2019s ID for the user that is making the API
    call, since every user has a different favorites collection_id.\nThe Add/Remove
    API handling will check all ids passed in before performing any add/removal operations.
    If any collection ids are malformed or do not exist in the user\u2019s account,
    the API call will throw a 400. Only if all of the collection ids are valid will
    the adds and removals be carried out."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}
  tags: Documents,Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-put-openapi.md
- name: Box Delete Folder
  x-api-slug: box
  description: Used to delete a folder. A recursive parameter must be included in
    order to delete folders that have items inside of them. An optional If-Match header
    can be included to ensure that client only deletes the folder if it knows about
    the latest version.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}
  tags: Documents,Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-delete-openapi.md
- name: Box Restore Folder
  x-api-slug: box
  description: Restores an item that has been moved to the trash. Default behavior
    is to restore the item to the folder it was in before it was moved to the trash.
    If that parent folder no longer exists or if there is now an item with the same
    name in that parent folder, the new parent folder and/or new name will need to
    be included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}
  tags: Documents,Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-id-post-openapi.md
- name: "Box Get Folder\u2019s Items"
  x-api-slug: box
  description: Retrieves the files and/or folders contained within this folder without
    any other metadata about the folder. Any attribute in the full files or folders
    objects can be passed in with the fields parameter to get specific attributes,
    and only those specific attributes back; otherwise, the mini format is returned
    for each item by default. Multiple attributes can be passed in separated by commas
    e.g. fields=name,created_at. Paginated results can be retrieved using the limit
    and offset parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/items
  tags: Documents,Folders, Folder, , Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-iditems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-iditems-get-openapi.md
- name: Box Copy Folder
  x-api-slug: box
  description: Used to create a copy of a folder in another folder. The original version
    of the folder will not be altered.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/copy
  tags: Documents,Folders, Folder, , Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idcopy-post-openapi.md
- name: Box Get Folder Collaborations
  x-api-slug: box
  description: Use this to get a list of all the collaborations on a folder i.e. all
    of the users that have access to that folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/collaborations
  tags: Documents,Folders, Folder, , Collaborations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idcollaborations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idcollaborations-get-openapi.md
- name: Box Get Trashed Folder
  x-api-slug: box
  description: Retrieves an folder that has been moved to the trash.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/trash
  tags: Documents,Folders, Folder, , Trash
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idtrash-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idtrash-get-openapi.md
- name: Box Permanently Delete
  x-api-slug: box
  description: Permanently deletes an folder that is in the trash. The item will no
    longer exist in Box. This action cannot be undone.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/trash
  tags: Documents,Folders, Folder, , Trash
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idtrash-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idtrash-delete-openapi.md
- name: Box Get Trashed Items
  x-api-slug: box
  description: Retrieves the files and/or folders that have been moved to the trash.
    Any attribute in the full files or folders objects can be passed in with the fields
    parameter to get specific attributes, and only those specific attributes back;
    otherwise, the mini format is returned for each item by default. Multiple attributes
    can be passed in separated by commas e.g. fields=name,created_at. Paginated results
    can be retrieved using the limit and offset parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/trash/items
  tags: Documents,Folders, Trash, Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/folderstrashitems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/folderstrashitems-get-openapi.md
- name: Box Get Watermark on Folder
  x-api-slug: box
  description: Used to retrieve the watermark for a corresponding Box folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/watermark
  tags: Documents,Folders, Folder, , Watermark
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idwatermark-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idwatermark-get-openapi.md
- name: Box Apply Watermark on Folder
  x-api-slug: box
  description: Used to apply or update the watermark for a corresponding Box folder.
    The endpoints accepts a JSON body describing the watermark to apply.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/watermark
  tags: Documents,Folders, Folder, , Watermark
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idwatermark-put-openapi.md
- name: Box Remove Watermark on Folder
  x-api-slug: box
  description: Used to remove the watermark for a corresponding Box Folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/watermark
  tags: Documents,Folders, Folder, , Watermark
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idwatermark-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idwatermark-delete-openapi.md
- name: Box Get All Metadata on Folder
  x-api-slug: box
  description: Used to retrieve all metadata associated with a given folder
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/metadata
  tags: Documents,Folders, Folder, , Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadata-get-openapi.md
- name: Box Create Metadata on Folder
  x-api-slug: box
  description: Used to create the metadata template instance for a corresponding Box
    folder. When creating metadata, only values that adhere to the metadata template
    schema will be accepted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/metadata/{SCOPE}/{TEMPLATE}
  tags: Documents,Folders, Folder, , Metadata, Scope, Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-post-openapi.md
- name: Box Get Metadata on Folder
  x-api-slug: box
  description: Used to retrieve the metadata template instance for a corresponding
    Box folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/metadata/{SCOPE}/{TEMPLATE}
  tags: Documents,Folders, Folder, , Metadata, Scope, Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-get-openapi.md
- name: Box Update Metadata on Folder
  x-api-slug: box
  description: Used to update the template instance. Updates can be either add, replace,
    remove , or test. The template instance can only be updated if the template instance
    already exists. When editing metadata, only values that adhere to the metadata
    template schema will be accepted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/metadata/{SCOPE}/{TEMPLATE}
  tags: Documents,Folders, Folder, , Metadata, Scope, Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-put-openapi.md
- name: Box Delete Metadata on Folder
  x-api-slug: box
  description: Used to delete the template instance. To delete custom key:value pairs
    within a template instance, you should refer to the updating metadata section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//folders/{FOLDER_ID}/metadata/{SCOPE}/{TEMPLATE}
  tags: Documents,Folders, Folder, , Metadata, Scope, Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/foldersfolder-idmetadatascopetemplate-delete-openapi.md
- name: Box Move User's Folder
  x-api-slug: box
  description: "Moves all of the owned content from within one user\u2019s folder
    into a new folder in another user\u2019s account. You can move folders across
    users as long as the you have administrative permissions and the \u2018source\u2019
    user owns the folders. To move everything from the root folder, use \u201C0\u201D
    which always represents the root folder of a Box account."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//users/{USER_ID}/folders/{FOLDER_ID}
  tags: Documents,Users, User, , Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/usersuser-idfoldersfolder-id-put-openapi.md
- name: Box
  x-api-slug: box
  description: Box.net provides a sophisticated API for their online document sharing
    and collaboration web application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/box/openapi.md
x-common:
- type: x-base
  url: https://api.box.com/
- type: x-blog
  url: http://blog.box.com/
- type: x-blog-rss
  url: http://blog.box.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/box
- type: x-crunchbase
  url: https://crunchbase.com/organization/box
- type: x-developer
  url: http://developers.box.com
- type: x-github
  url: https://github.com/boxdotnet
- type: x-pricing
  url: https://developers.box.com/box-platform-pricing/
- type: x-road-map
  url: https://developers.box.com/roadmap/
- type: x-twitter
  url: https://twitter.com/BoxPlatform
- type: x-twitter
  url: https://twitter.com/BoxHQ
- type: x-website
  url: http://box.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
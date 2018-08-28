---
name: SugarSync
x-slug: sugarsync
description: SugarSync is a cloud file sharing, file sync and online backup service
  that is simple, powerful and easy to use. Unlike Dropbox, SugarSync enables you
  to back up your existing folder structure. Try it for FREE for 30 days and get started
  today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
x-kinRank: "8"
x-alexaRank: "64898"
tags: Folders
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/apis.md
specificationVersion: "0.14"
apis:
- name: Sugar Sync  API - Retrieving Folder Information
  x-api-slug: folder-get
  description: To retrieve information about a folder, an application submits an HTTP
    GET request to then          folder resource that represents the folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-openapi.md
- name: Sugar Sync  API - Deleting a Folder
  x-api-slug: folder-delete
  description: An application can permanantly delete a folder by issuing an HTTP DELETE
    request to the URL of thenfolder resource.nIts a good idea to precede DELETE requests
    like this with a caution note in your applications user interface.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-delete-openapi.md
- name: Sugar Sync  API - Retrieving Folder Contents
  x-api-slug: folder-get
  description: To retrieve the contents of a folder, an application submits an HTTP
    GET request to the URLn          that represents the folder contents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-openapi.md
- name: Sugar Sync  API - Creating a Folder
  x-api-slug: folder-post
  description: An application can create a folder within another folder by issuing
    an HTTP POST request to the URL ofnthe containing folder resource.nIn addition,
    the application needs to provide as input, XML that identifies the display name
    of the folder to be created.nNote that an application can create a folder only
    within another folder, and not directly in a workspace.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-post-openapi.md
- name: Sugar Sync  API - Updating Folder Information
  x-api-slug: folder-put
  description: An application can update various attributes of a folder by issuing
    an HTTP PUT request to the URL thatnrepresents the folder resource. In addition,
    the app needs to provide as input, XML that identifies the new attribute values
    for the folder. Upon receiving the PUT request, the SugarSync service examines
    the input and updates any of the attributes that have been modified.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-put-openapi.md
- name: Sugar Sync  API - Updating Folder Information
  x-api-slug: folder-put
  description: An application can update various attributes of a folder by issuing
    an HTTP PUT request to the URL thatnrepresents the folder resource. In addition,
    the app needs to provide as input, XML that identifies the new attribute values
    for the folder. Upon receiving the PUT request, the SugarSync service examines
    the input and updates any of the attributes that have been modified.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-put-openapi.md
- name: Sugar Sync  API - Creating a Folder
  x-api-slug: folder-post
  description: An application can create a folder within another folder by issuing
    an HTTP POST request to the URL ofnthe containing folder resource.nIn addition,
    the application needs to provide as input, XML that identifies the display name
    of the folder to be created.nNote that an application can create a folder only
    within another folder, and not directly in a workspace.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-post-openapi.md
- name: Sugar Sync  API - Retrieving Folder Contents
  x-api-slug: folder-get
  description: To retrieve the contents of a folder, an application submits an HTTP
    GET request to the URLn          that represents the folder contents.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-openapi.md
- name: Sugar Sync  API - Deleting a Folder
  x-api-slug: folder-delete
  description: An application can permanantly delete a folder by issuing an HTTP DELETE
    request to the URL of thenfolder resource.nIts a good idea to precede DELETE requests
    like this with a caution note in your applications user interface.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-delete-openapi.md
- name: Sugar Sync  API - Retrieving Folder Information
  x-api-slug: folder-get
  description: To retrieve information about a folder, an application submits an HTTP
    GET request to then          folder resource that represents the folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/488-sugarsync-.jpg
  humanURL: http://sugarsync.com
  baseURL: https://api.sugarsync.com//
  tags: Cloud, Storage, Storage, File, Storage, Target, Getting Started Example, Stack
    Network, Technology, Mobile, SaaS, internet, Relative Data, Service API, Relative
    StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/sugarsync/folder-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://stripe.api.gallery.streamdata.io
- type: x-api-stack
  url: http://sugarsync..stack.network
- type: x-application-gallery
  url: https://www.sugarsync.com/partners/
- type: x-base
  url: https://api.sugarsync.com
- type: x-best-practices
  url: https://www.sugarsync.com/dev/best-practices.html
- type: x-blog
  url: http://www.sugarsync.com/blog
- type: x-blog-rss
  url: http://blog.sugarsync.com/blog/feed
- type: x-crunchbase
  url: https://crunchbase.com/organization/sugarsync
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sugarsync
- type: x-developer
  url: https://www.sugarsync.com/developer
- type: x-forum
  url: https://groups.google.com/a/developers.sugarsync.com/forum/#!forum/platform-api/join
- type: x-getting-started
  url: https://www.sugarsync.com/dev/getting-started.html
- type: x-glossary
  url: https://www.sugarsync.com/dev/glossary.html
- type: x-linkedin
  url: https://www.linkedin.com/company/sugarsync
- type: x-pricing
  url: https://www.sugarsync.com/
- type: x-selfservice-registration
  url: https://www.sugarsync.com/developer/signup
- type: x-terms-of-service
  url: https://www.sugarsync.com/dev/terms.html
- type: x-twitter
  url: https://twitter.com/SugarSync
- type: x-website
  url: http://sugarsync.com
- type: x-website
  url: http://www.sugarsync.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
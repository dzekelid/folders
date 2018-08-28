---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Folders
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Child Folders
  x-api-slug: mecontactfoldersidchildfolders-get
  description: List childFolders Get a collection of child folders under the specified
    contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API - List Child Folders
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-get
  description: List childFolders Get a collection of child folders under the specified
    contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API - List Child Folders
  x-api-slug: memailfoldersidchildfolders-get
  description: List childFolders Get the folder collection under the specified folder.
    You can use the .../me/MailFolders shortcut to get the top-level folder collection
    and navigate to another folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API - List Child Folders
  x-api-slug: usersid--userprincipalnamemailfoldersidchildfolders-get
  description: List childFolders Get the folder collection under the specified folder.
    You can use the .../me/MailFolders shortcut to get the top-level folder collection
    and navigate to another folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-get-openapi.md
- name: Microsoft Graph API - List Contact Folders
  x-api-slug: usersid--userprincipalnamecontactfolders-get
  description: List contactFolders Get the contact folder collection in the default
    Contacts folder of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API - List Mail Folders
  x-api-slug: usersid--userprincipalnamemailfolders-get
  description: List mailFolders Get the mail folder collection under the root folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-get-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: mecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: mecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: mecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: medriverootchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriverootchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriverootchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: medriveitemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: drivesdriveiditemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: groupsgroupiddriveitemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Mail Folder Copy
  x-api-slug: memailfoldersidcopy-post
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API - Mail Folder Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidcopy-post
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API - Delete Mail Folder
  x-api-slug: memailfoldersid-delete
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersid-delete
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-openapi.md
- name: Microsoft Graph API - Get Mail Folder
  x-api-slug: memailfoldersid-get
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersid-get
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-openapi.md
- name: Microsoft Graph API - Mail Folder Move
  x-api-slug: memailfoldersidmove-post
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidmove-post-openapi.md
- name: Microsoft Graph API - Mail Folder Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmove-post
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: memailfoldersidchildfolders-post
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersidchildfolders-post
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfolders-post
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: usersid--userprincipalnamemailfolders-post
  description: Create MailFolder Use this API to create a new mail folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: usersid--userprincipalnamemailfolders-post
  description: Create MailFolder Use this API to create a new mail folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfolders-post
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersidchildfolders-post
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Mail Folder
  x-api-slug: memailfoldersidchildfolders-post
  description: Create MailFolder Use this API to create a new child mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Mail Folder Move
  x-api-slug: usersid--userprincipalnamemailfoldersidmove-post
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmove-post-openapi.md
- name: Microsoft Graph API - Mail Folder Move
  x-api-slug: memailfoldersidmove-post
  description: 'mailFolder: move Move a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidmove-post-openapi.md
- name: Microsoft Graph API - Get Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersid-get
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Mail Folder
  x-api-slug: memailfoldersid-get
  description: Get mailFolder Retrieve the properties and relationships of mailfolder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-get-openapi.md
- name: Microsoft Graph API - Delete Mail Folder
  x-api-slug: usersid--userprincipalnamemailfoldersid-delete
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Mail Folder
  x-api-slug: memailfoldersid-delete
  description: Delete mailFolder Delete mailFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersid-delete-openapi.md
- name: Microsoft Graph API - Mail Folder Copy
  x-api-slug: usersid--userprincipalnamemailfoldersidcopy-post
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API - Mail Folder Copy
  x-api-slug: memailfoldersidcopy-post
  description: 'mailFolder: copy Copy a mailfolder and its contents to another mailfolder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/memailfoldersidcopy-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: groupsgroupiddriveitemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/groupsgroupiddriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: drivesdriveiditemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/drivesdriveiditemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: medriveitemsparentitemidchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriveitemsparentitemidchildren-post-openapi.md
- name: Microsoft Graph API - Create A New Folder
  x-api-slug: medriverootchildren-post
  description: Create a new folder Create a new folder or DriveItem in a Drive with
    a specified parent item or path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriverootchildren-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/medriverootchildren-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: mecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: mecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: mecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
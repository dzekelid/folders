---
name: Microsoft Office 365
x-slug: microsoft-office-365
description: Integrate Office 365 REST APIs powered by Microsoft Graph into your own
  app to connect to files, calendars, mail and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Folders
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Office 365 Get Contact Folders Contact Folder
  x-api-slug: microsoft-office-365
  description: You can access the default contact folder by using the const...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}
  tags: Contactfolders, Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-get-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}
  tags: Contactfolders, Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-parameters-openapi.md
- name: Microsoft Office 365 Get Contact Folders Contact Folder Childfolders
  x-api-slug: microsoft-office-365
  description: All non-default contact folders are stored as children of th...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/ChildFolders
  tags: Contactfolders, Contact, Folder, , Childfolders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-get-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder Childfolders
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder  childfolders
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/ChildFolders
  tags: Contactfolders, Contact, Folder, , Childfolders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-parameters-openapi.md
- name: Microsoft Office 365 Get Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: You can request all contacts (or a filtered set by using the...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-get-openapi.md
- name: Microsoft Office 365 Add Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: You can create a contact by sending a POST request with a JS...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-post-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder  contacts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-parameters-openapi.md
- name: Microsoft Office 365 Get Folders Folder
  x-api-slug: microsoft-office-365
  description: You can retrieve information about other folders by using th...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-get-openapi.md
- name: Microsoft Office 365 Add Folders Folder
  x-api-slug: microsoft-office-365
  description: You can create a folder by sending a POST request with a JSO...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-post-openapi.md
- name: Microsoft Office 365 Delete Folders Folder
  x-api-slug: microsoft-office-365
  description: To delete a folder, send a DELETE request to the URL of the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-delete-openapi.md
- name: Microsoft Office 365 Patch Folders Folder
  x-api-slug: microsoft-office-365
  description: You can update a folder by sending a PATCH request with a JS...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Folders Folder
  x-api-slug: microsoft-office-365
  description: Parameters folders folder
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-id-parameters-openapi.md
- name: Microsoft Office 365 Get Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can request all the emails and meeting requests in a fol...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-openapi.md
- name: Microsoft Office 365 Add Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can create an email by sending a POST request with a JSO...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-idmessages-post-openapi.md
- name: Microsoft Office 365 Parameters Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: Parameters folders folder  messages
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-openapi.md
- name: Microsoft Office 365
  x-api-slug: microsoft-office-365
  description: Integrate Office 365 REST APIs powered by Microsoft Graph into your
    own app to connect to files, calendars, mail and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/microsoft-office-365/openapi.md
x-common:
- type: x-developer
  url: http://dev.office.com
- type: x-github
  url: https://github.com/OfficeDev
- type: x-twitter
  url: https://twitter.com/OfficeDev
- type: x-website
  url: http://office.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
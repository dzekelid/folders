---
name: AWS WorkDocs
x-slug: aws-workdocs
description: Amazon WorkDocs is a fully managed, secure enterprise storage and sharing
  service with strong administrative controls and feedback capabilities that improve
  user productivity.Users can comment on files, send them to others for feedback,
  and upload new versions without having to resort to emailing multiple versions of
  their files as attachments. Users can take advantage of these capabilities wherever
  they are, using the device of their choice, including PCs, Macs, tablets and phones.
  Amazon WorkDocs offers IT administrators the option of integrating with existing
  corporate directories, flexible sharing policies and control of the location where
  data is stored. Customers can get started using Amazon WorkDocs with a 30-day free
  trial providing 1 TB of storage per user for up to 50 users.Amazon WorkDocs offers
  an Administrative SDK, currently in public preview. The Administrative SDK allows
  you to integrate your applications with Amazon WorkDocs by performing content and
  permissions updates, and managing users, programmatically. You can sign-up for the
  public preview here.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Folders
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/apis.md
specificationVersion: "0.14"
apis:
- name: AWS WorkDocs API Create Folder
  x-api-slug: aws-workdocs-api
  description: Creates a folder with the specified name and parent folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=CreateFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actioncreatefolder-get-openapi.md
- name: AWS WorkDocs API Delete Folder
  x-api-slug: aws-workdocs-api
  description: Permanently deletes the specified folder and its contents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actiondeletefolder-get-openapi.md
- name: AWS WorkDocs API Delete Folder Contents
  x-api-slug: aws-workdocs-api
  description: Deletes the contents of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteFolderContents
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actiondeletefoldercontents-get-openapi.md
- name: AWS WorkDocs API Describe Folder Contents
  x-api-slug: aws-workdocs-api
  description: Describes the contents of the specified folder, including its documents
    and sub-folders.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeFolderContents
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actiondescribefoldercontents-get-openapi.md
- name: AWS WorkDocs API Get Folder
  x-api-slug: aws-workdocs-api
  description: Retrieves the metadata of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actiongetfolder-get-openapi.md
- name: AWS WorkDocs API Get Folder Path
  x-api-slug: aws-workdocs-api
  description: Retrieves the path information (the hierarchy from the root folder)
    for the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetFolderPath
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actiongetfolderpath-get-openapi.md
- name: AWS WorkDocs API Update Folder
  x-api-slug: aws-workdocs-api
  description: Updates the specified attributes of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=UpdateFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/actionupdatefolder-get-openapi.md
- name: AWS WorkDocs API
  x-api-slug: aws-workdocs-api
  description: Amazon WorkDocs is a fully managed, secure enterprise storage and sharing
    service with strong administrative controls and feedback capabilities that improve
    user productivity.Users can comment on files, send them to others for feedback,
    and upload new versions without having to resort to emailing multiple versions
    of their files as attachments. Users can take advantage of these capabilities
    wherever they are, using the device of their choice, including PCs, Macs, tablets
    and phones. Amazon WorkDocs offers IT administrators the option of integrating
    with existing corporate directories, flexible sharing policies and control of
    the location where data is stored. Customers can get started using Amazon WorkDocs
    with a 30-day free trial providing 1 TB of storage per user for up to 50 users.Amazon
    WorkDocs offers an Administrative SDK, currently in public preview. The Administrative
    SDK allows you to integrate your applications with Amazon WorkDocs by performing
    content and permissions updates, and managing users, programmatically. You can
    sign-up for the public preview here.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: :///
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/folders/master/_listings/aws-workdocs/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/workdocs/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/workdocs/faqs/
- type: x-forum
  url: https://aws.amazon.com/workdocs/resources/#forum
- type: x-pricing
  url: https://aws.amazon.com/workdocs/pricing/
- type: x-sdk
  url: https://aws.amazon.com/workdocs/developers/
- type: x-website
  url: https://aws.amazon.com/workdocs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
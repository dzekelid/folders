swagger: "2.0"
x-collection-name: Context.IO
x-complete: 1
info:
  title: Context.IO
  description: context-io-is-the-missing-email-api-that-makes-it-easy-and-fast-to-integrate-your-users-email-data-in-your-application-
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/sources/{label}/folders:
    get:
      summary: Get Accounts Sources Label Folders
      description: Lists folders in an IMAP source. Returns folders existing in a
        given IMAP account.
      operationId: listAccountSourceFolders_
      x-api-path-slug: accountsidsourceslabelfolders-get
      parameters:
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: path
        name: label
        description: The label property of the source instance
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Sources
      - Label
      - Folders
  /accounts/{id}/sources/{label}/folders/{folder}:
    put:
      summary: Put Accounts Sources Label Folders Folder
      description: |-
        Creates a folder on an IMAP source. A new folder can be added to an IMAP source by PUTting the desired path under the sources/folders resource.
        Working with server-specific hierarchy delimiters:
        IMAP servers are free to use the character they want as the folder hierarchy delimiter. The bad news is they don't use the same. The good news is you don't need to know this, we take care of it.

        Then what is that delim parameter for?
        Good question. By default, we expect you to specify the folder hierarchy using / as the hierarchy delimiter. For example, to create a folder called my folder under the folder base folder, you would call:
        PUT /2.0/accounts/<id>/sources/<label>/folders/base+folder/my+folder

        No matter what's the actual hierarchy delimiter the IMAP server expects, this call will work. However, say you need to use another character as the delimiter, here's how you'd do it:
        PUT /2.0/accounts/<id>/sources/<label>/folders/base+folder.my+folder?delim=.

        Both examples above are equivalent and will have the same result no matter what the IMAP server expects as the actual hierarchy delimiter.
      operationId: createAccountSourceFolder_
      x-api-path-slug: accountsidsourceslabelfoldersfolder-put
      parameters:
      - in: query
        name: delim
        description: If / isnt fancy enough as a hierarchy delimiter when specifying
          the folder you want to create, youre free to use what you want, just make
          sure you set this delim parameter to tell us what youre using
      - in: path
        name: folder
        description: The full folder path you want to create
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: path
        name: label
        description: The label property of the source instance
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Sources
      - Label
      - Folders
      - Folder
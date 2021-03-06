---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Parameters Contacts Contact Attachments
  description: Parameters contacts contact  attachments
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ContactFolders{contact_folder_id}/Contacts:
    get:
      summary: Get Contact Folders Contact Folder Contacts
      description: You can request all contacts (or a filtered set by using the...
      operationId: getContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    post:
      summary: Add Contact Folders Contact Folder Contacts
      description: You can create a contact by sending a POST request with a JS...
      operationId: postContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    parameters:
      summary: Parameters Contact Folders Contact Folder Contacts
      description: Parameters contactfolders contact folder  contacts
      operationId: parametersContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
  /Contacts{contact_id}:
    get:
      summary: Get Contacts Contact
      description: You can retrieve information about a specific contact by usi...
      operationId: getContactsContact
      x-api-path-slug: contactscontact-id-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    post:
      summary: Add Contacts Contact
      description: You can create a contact by sending a POST request with a JS...
      operationId: postContactsContact
      x-api-path-slug: contactscontact-id-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    delete:
      summary: Delete Contacts Contact
      description: You can delete a contact by simply sending a DELETE request ...
      operationId: deleteContactsContact
      x-api-path-slug: contactscontact-id-delete
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    patch:
      summary: Patch Contacts Contact
      description: To update a contact, send a PATCH request to the URL of the ...
      operationId: patchContactsContact
      x-api-path-slug: contactscontact-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    parameters:
      summary: Parameters Contacts Contact
      description: Parameters contacts contact
      operationId: parametersContactsContact
      x-api-path-slug: contactscontact-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
  /Contacts{contact_id}/Attachments:
    get:
      summary: Get Contacts Contact Attachments
      description: To get attachments, send a GET request to the Attachments pr...
      operationId: getContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    post:
      summary: Add Contacts Contact Attachments
      description: To add an attachment to an item, send a POST request to the ...
      operationId: postContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    delete:
      summary: Delete Contacts Contact Attachments
      description: To delete an attachment, send a DELETE request to the URL of...
      operationId: deleteContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-delete
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    parameters:
      summary: Parameters Contacts Contact Attachments
      description: Parameters contacts contact  attachments
      operationId: parametersContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-parameters
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
  /ContactFolders{contact_folder_id}:
    get:
      summary: Get Contact Folders Contact Folder
      description: You can access the default contact folder by using the const...
      operationId: getContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
    parameters:
      summary: Parameters Contact Folders Contact Folder
      description: Parameters contactfolders contact folder
      operationId: parametersContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
  /ContactFolders{contact_folder_id}/ChildFolders:
    get:
      summary: Get Contact Folders Contact Folder Childfolders
      description: All non-default contact folders are stored as children of th...
      operationId: getContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
    parameters:
      summary: Parameters Contact Folders Contact Folder Childfolders
      description: Parameters contactfolders contact folder  childfolders
      operationId: parametersContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
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
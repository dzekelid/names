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
tags: Names
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Names
  x-api-slug: workbookworksheetsidnamenames-get
  description: List names Retrieve a list of named item associated with the worksheet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-openapi.md
- name: Microsoft Graph API - Add Named Item
  x-api-slug: workbooknamesadd-post
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesadd-post-openapi.md
- name: Microsoft Graph API - Add Named Item
  x-api-slug: workbookworksheetsidnamenamesadd-post
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-openapi.md
- name: Microsoft Graph API - Get Named Item
  x-api-slug: workbooknamesltnamegt-get
  description: Get NamedItem Retrieve the properties and relationships of nameditem
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-get-openapi.md
- name: Microsoft Graph API - List Named Item Collection
  x-api-slug: workbooknames-get
  description: List NamedItemCollection Retrieve a list of nameditem objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknames-get-openapi.md
- name: Microsoft Graph API - Named Item Range
  x-api-slug: workbooknamesltnamegtrange-post
  description: 'NamedItem: Range Returns the range object that is associated with
    the name. Throws an exception if the named item''s type is not a range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-openapi.md
- name: Microsoft Graph API - Update Nameditem
  x-api-slug: workbooknamesltnamegt-patch
  description: Update nameditem Update the properties of nameditem object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-openapi.md
- name: Microsoft Graph API - Add Named Item
  x-api-slug: workbooknamesadd-post
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesadd-post-openapi.md
- name: Microsoft Graph API - Add Named Item
  x-api-slug: workbookworksheetsidnamenamesadd-post
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-openapi.md
- name: Microsoft Graph API - Get Named Item
  x-api-slug: workbooknamesltnamegt-get
  description: Get NamedItem Retrieve the properties and relationships of nameditem
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-get-openapi.md
- name: Microsoft Graph API - List Named Item Collection
  x-api-slug: workbooknames-get
  description: List NamedItemCollection Retrieve a list of nameditem objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknames-get-openapi.md
- name: Microsoft Graph API - Named Item Range
  x-api-slug: workbooknamesltnamegtrange-post
  description: 'NamedItem: Range Returns the range object that is associated with
    the name. Throws an exception if the named item''s type is not a range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-openapi.md
- name: Microsoft Graph API - Update Nameditem
  x-api-slug: workbooknamesltnamegt-patch
  description: Update nameditem Update the properties of nameditem object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-openapi.md
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
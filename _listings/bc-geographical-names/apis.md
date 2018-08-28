---
name: BC Geographical Names
x-slug: bc-geographical-names
description: Geographical names are more than labels on maps and road signs. They
  can reveal patterns of settlement, exploration and migration, and mirror outside
  influences to our history - aspects of the heritage and promise of an area that
  might otherwise be overlooked or forgotten by visitors and later generations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Names
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/apis.md
specificationVersion: "0.14"
apis:
- name: BC Geographical Names - Search for names with metadata changes in a given
    period
  x-api-slug: nameschanges-get
  description: Search for information about geographical names which have changed
    most recently within a specified time window.  Changes may include status cupdates
    and metadata corrections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/nameschanges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/nameschanges-get-openapi.md
- name: BC Geographical Names - Search for names affected by recent naming decision
  x-api-slug: namesdecisionsrecent-get
  description: Search for information about geographical names affected by naming
    'decisions' made by the BC Geographical Names Office (naming authority) within
    the last X days.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesdecisionsrecent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesdecisionsrecent-get-openapi.md
- name: BC Geographical Names - Search for names affected by naming decisions in a
    given year
  x-api-slug: namesdecisionsyear-get
  description: Search for information about geographical names affected by naming
    'decisions' made by the BC Geographical Names Office (naming authority) in a given
    year.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesdecisionsyear-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesdecisionsyear-get-openapi.md
- name: BC Geographical Names - Search in a geographic area
  x-api-slug: namesinside-get
  description: Search for information about geographical names that correspond to
    features within a geographic bounding box.  Various options and filter parameters
    are available to refine the search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesinside-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesinside-get-openapi.md
- name: BC Geographical Names - Search near to a geographic point
  x-api-slug: namesnear-get
  description: Search for information about geographical names that correspond to
    features within a geographic area defined by a centre point and a radius.  Various
    options and filter parameters are available to refine the search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnear-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnear-get-openapi.md
- name: BC Geographical Names - Search by name, limit to unofficial names only
  x-api-slug: namesnotofficialsearch-get
  description: Search for information about unofficial geographical names by the text
    of the name itself.  Various options and filter parameters are available to refine
    the search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnotofficialsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnotofficialsearch-get-openapi.md
- name: BC Geographical Names - Search by name, limit to official names only
  x-api-slug: namesofficialsearch-get
  description: Search for information about official geographical names by the text
    of the name itself.  Various options and filter parameters are available to refine
    the search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesofficialsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesofficialsearch-get-openapi.md
- name: BC Geographical Names - Search by name
  x-api-slug: namessearch-get
  description: Search for information about geographical names by the text of the
    name itself.  The response will include both official and unofficial names.  Various
    options and filter parameters are available to refine the search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namessearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namessearch-get-openapi.md
- name: BC Geographical Names - Get a name by its nameId
  x-api-slug: namesnameid-outputformat-get
  description: Get information about the geographical name with the specified nameId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-openapi.md
- name: BC Geographical Names - Get a name by its nameId
  x-api-slug: namesnameid-outputformat-get
  description: Get information about the geographical name with the specified nameId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-openapi.md
- name: BC Geographical Names - Get a name by its nameId
  x-api-slug: namesnameid-outputformat-get
  description: Get information about the geographical name with the specified nameId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-openapi.md
- name: BC Geographical Names - Get a name by its nameId
  x-api-slug: namesnameid-outputformat-get
  description: Get information about the geographical name with the specified nameId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/names/master/_listings/bc-geographical-names/namesnameid-outputformat-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bbc.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bc.geographical.names.stack.network
- type: x-website
  url: https://apps.gov.bc.ca/pub/bcgnws/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
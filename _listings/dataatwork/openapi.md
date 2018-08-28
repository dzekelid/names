swagger: "2.0"
x-collection-name: DataAtWork
x-complete: 1
info:
  title: Open Skills API
  description: a-complete-and-standard-data-store-for-canonical-and-emerging-skills-knowledge-abilities-tools-technolgies-and-how-they-relate-to-jobs-
  contact:
    name: Work Data Initiative
    url: http://www.dataatwork.org
  version: "1.0"
host: api.dataatwork.org
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /skills:
    get:
      summary: Skill Names and Descriptions
      description: Retrieve the names, descriptions, and UUIDs of all skills.
      operationId: retrieve-the-names-descriptions-and-uuids-of-all-skills
      x-api-path-slug: skills-get
      parameters:
      - in: query
        name: limit
        description: Maximum number of items per page
      - in: query
        name: offset
        description: Pagination offset
      responses:
        200:
          description: OK
      tags:
      - Skill
      - Names
      - Descriptions
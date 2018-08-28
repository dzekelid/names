swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /by_id/names:
    get:
      summary: Get By Names
      description: Get a listing of links by fullname.
      operationId: get&nbsp;ByNames
      x-api-path-slug: by-idnames-get
      parameters:
      - in: query
        name: names
        description: A comma-separated list of link fullnames
        type: string
      responses:
        200:
          description: OK
      tags:
      - Names
  /api/search_reddit_names.json:
    get:
      summary: Get Search Reddit Names
      description: List subreddit names that begin with a query string.
      operationId: get&nbsp;SearchRedditNames
      x-api-path-slug: apisearch-reddit-names-json-get
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Reddit
      - Names
  /search_reddit_names:
    post&nbsp;:
      summary: Add Search Reddit Names
      description: List subreddit names that begin with a query string.
      operationId: post&nbsp;SearchRedditNames
      x-api-path-slug: search-reddit-names-postnbsp
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Reddit
      - Names
---
swagger: "2.0"
x-collection-name: Trello
x-complete: 1
info:
  title: Trello
  description: this-document-describes-the-rest-api-of-trello-as-published-by-trello-com---a-hrefhttpstrello-comdocsindex-html-target-blankofficial-documentationa--a-hrefhttpstrello-comdocsapi-target-blankthe-html-pages-that-were-scraped-in-order-to-generate-this-specification-a
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /boards/{idBoard}/labelNames/blue:
    put:
      summary: Put Boards Label Names Blue
      description: Put boards label names blue.
      operationId: updateBoardsLabelNamesBlueByIdBoard
      x-api-path-slug: boardsidboardlabelnamesblue-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Blue to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Blue
  /boards/{idBoard}/labelNames/green:
    put:
      summary: Put Boards Label Names Green
      description: Put boards label names green.
      operationId: updateBoardsLabelNamesGreenByIdBoard
      x-api-path-slug: boardsidboardlabelnamesgreen-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Green to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Green
  /boards/{idBoard}/labelNames/orange:
    put:
      summary: Put Boards Label Names Orange
      description: Put boards label names orange.
      operationId: updateBoardsLabelNamesOrangeByIdBoard
      x-api-path-slug: boardsidboardlabelnamesorange-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Orange to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Orange
  /boards/{idBoard}/labelNames/purple:
    put:
      summary: Put Boards Label Names Purple
      description: Put boards label names purple.
      operationId: updateBoardsLabelNamesPurpleByIdBoard
      x-api-path-slug: boardsidboardlabelnamespurple-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Purple to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Purple
  /boards/{idBoard}/labelNames/red:
    put:
      summary: Put Boards Label Names Red
      description: Put boards label names red.
      operationId: updateBoardsLabelNamesRedByIdBoard
      x-api-path-slug: boardsidboardlabelnamesred-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Red to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Red
  /boards/{idBoard}/labelNames/yellow:
    put:
      summary: Put Boards Label Names Yellow
      description: Put boards label names yellow.
      operationId: updateBoardsLabelNamesYellowByIdBoard
      x-api-path-slug: boardsidboardlabelnamesyellow-put
      parameters:
      - in: body
        name: body
        description: Attributes of Label Names Yellow to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Label
      - Names
      - Yellow
---
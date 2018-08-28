swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/catalog/analytics/{name}/versions:
    delete:
      summary: Delete all versions of the named analytic.
      description: Given the name of an analytic, this API deletes all its versions.
      operationId: deleteAllVersions
      x-api-path-slug: apiv1cataloganalyticsnameversions-delete
      parameters:
      - in: path
        name: name
        description: analytic name
      responses:
        2:
          description: Successful response
      tags:
      - Versions
      - Of
      - Named
      - Analytic
  /v1/collections/{collectionName}/features:
    delete:
      summary: Delete from the named collection all features with a matching GeoJSON
        id.
      description: Delete from the named collection all features with a matching GeoJSON
        id. This could be 0, 1 or many features.
      operationId: delete-from-the-named-collection-all-features-with-a-matching-geojson-id-this-could-be-0-1-or-many-f
      x-api-path-slug: v1collectionscollectionnamefeatures-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - From
      - Named
      - Collection
      - ""
      - Features
      - Matching
      - GeoJSON
      - Id
---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Gigme Place Placeunique
  version: 1.0.0
  description: Get gigme place placeunique.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/art/{unique}/details:
    get:
      summary: Get Art Unique Details
      description: Get art unique details.
      operationId: getApiV1ArtUniqueDetails
      x-api-path-slug: apiv1artuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Art
      - Unique
      - Details
  /api/v1/event/{unique}/details:
    get:
      summary: Get Event Unique Details
      description: Get event unique details.
      operationId: getApiV1EventUniqueDetails
      x-api-path-slug: apiv1eventuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Event
      - Unique
      - Details
  /api/v1/gigme/artist/{unique}/details:
    get:
      summary: Get Gigme Artist Unique Details
      description: Get gigme artist unique details.
      operationId: getApiV1GigmeArtistUniqueDetails
      x-api-path-slug: apiv1gigmeartistuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Unique
      - Details
  /api/v1/gigme/event/{unique}/details:
    get:
      summary: Get Gigme Event Unique Details
      description: Get gigme event unique details.
      operationId: getApiV1GigmeEventUniqueDetails
      x-api-path-slug: apiv1gigmeeventuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Unique
      - Details
  /api/v1/gigme/place/{placeUnique}:
    get:
      summary: Get Gigme Place Placeunique
      description: Get gigme place placeunique.
      operationId: getApiV1GigmePlacePlaceunique
      x-api-path-slug: apiv1gigmeplaceplaceunique-get
      parameters:
      - in: path
        name: placeUnique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeunique
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
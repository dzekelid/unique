---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Gigme Artist Unique Details
  version: 1.0.0
  description: Get gigme artist unique details.
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
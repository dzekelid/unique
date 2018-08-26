---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 1
info:
  title: Dyn
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  reports/clicks/unique:
    get:
      summary: Unique Click Report
      description: Returns a list of unique links clicked for the specified account
        during the specified date range. Including a date range is highly recommended.
      operationId: getReportsClicksUnique
      x-api-path-slug: reportsclicksunique-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: startindex
        description: Starting index value (optional)
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Unique
      - Click
      - Report
---
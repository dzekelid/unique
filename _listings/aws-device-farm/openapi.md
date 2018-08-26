---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 1
info:
  title: AWS Device Farm API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListUniqueProblems:
    get:
      summary: List Unique Problems
      description: Gets information about unique problems.
      operationId: listUniqueProblems
      x-api-path-slug: actionlistuniqueproblems-get
      parameters:
      - in: query
        name: arn
        description: The unique problems ARNs
        type: string
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous call to this
          operation, which can be used to return the next set of items in the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unique Problems
---
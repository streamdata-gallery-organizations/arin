---
swagger: "2.0"
x-collection-name: ARIN
x-complete: 0
info:
  title: Reverse DNS API List Nets
  description: lists networks related to a give delegation.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rdns:
    get:
      summary: Reverse DNS
      description: ""
      operationId: rdns
      x-api-path-slug: rdns-get
      parameters:
      - in: query
        name: delegation name
        description: the name of the delegation
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Reverse DNS
  /rdns/nets:
    get:
      summary: List Nets
      description: lists networks related to a give delegation.
      operationId: rdnsNets
      x-api-path-slug: rdnsnets-get
      responses:
        200:
          description: OK
      tags:
      - RDNS
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
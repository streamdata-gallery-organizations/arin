---
swagger: "2.0"
x-collection-name: ARIN
x-complete: 1
info:
  title: Reverse DNS API
  description: for-managing-reverse-dns-
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
---
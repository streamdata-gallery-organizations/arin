---
swagger: "2.0"
x-collection-name: ARIN
x-complete: 0
info:
  title: Customers API Manage customers
  description: ""
  version: "1.0"
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /asn:
    get:
      summary: Autonomous System Number(s)
      description: ""
      operationId: asn
      x-api-path-slug: asn-get
      parameters:
      - in: query
        name: handle
        description: the handle of the ASN
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Autonomous Systen Numbers
  /asn/pocs:
    get:
      summary: List POCs
      description: lists the POCs associated with a given ASN.
      operationId: asnPocs
      x-api-path-slug: asnpocs-get
      responses:
        200:
          description: OK
      tags:
      - POCs
  cidr/:
    get:
      summary: IP and CIDR Queries
      description: ""
      operationId: cidr
      x-api-path-slug: cidr-get
      responses:
        200:
          description: OK
      tags:
      - CIDR
  /customers:
    get:
      summary: Manage customers
      description: ""
      operationId: customers
      x-api-path-slug: customers-get
      parameters:
      - in: query
        name: handle
        description: the handle of the customer
        type: string
        format: string
      - in: query
        name: name
        description: the name of the customer
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Customers
host: whois.arin.net
basePath: /rest
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
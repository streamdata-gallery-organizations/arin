---
swagger: "2.0"
x-collection-name: ARIN
x-complete: 0
info:
  title: Delegation API Add Delegation
  description: This call will add the single nameserver specified in your URL to the
    Delegation specified in your URL, and return a payload containing that Delegation's
    information after the nameserver has been added.
  version: 1.0.0
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
  /delegation:
    get:
      summary: Get Delegation
      description: This call will return a payload containing details about the Delegation
        specified in your URL.
      operationId: getDelegation
      x-api-path-slug: delegation-get
      responses:
        200:
          description: OK
      tags:
      - Delegation
    put:
      summary: Update Delegation
      description: This call will modify the details of the Delegation specified in
        your URL. When making this call, attach a Delegation Payload containing the
        details of the Delegation you intend to modify. To ensure accuracy, use Get
        Delegation to get the most current information before making changes. This
        call returns a payload containing that Delegation's information as it exists
        after modification.
      operationId: updateDelegation
      x-api-path-slug: delegation-put
      responses:
        200:
          description: OK
      tags:
      - Delegation
    post:
      summary: Add Delegation
      description: This call will add the single nameserver specified in your URL
        to the Delegation specified in your URL, and return a payload containing that
        Delegation's information after the nameserver has been added.
      operationId: addDelegation
      x-api-path-slug: delegation-post
      responses:
        200:
          description: OK
      tags:
      - Delegation
host: www.arin.net
basePath: /regrws/core/v1
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
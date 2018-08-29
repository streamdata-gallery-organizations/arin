---
swagger: "2.0"
info:
  title: Delegation API
  description: Delegations are entries that relate IP addresses to domain names using
    the Domain Name System (DNS) of the Internet. Delegations contain the information
    necessary for Reverse DNS, including the associated nameservers, and DNS Delegation
    Signer (DS Record) information. Delegations may not be created or deleted independently.
    They appear and disappear automatically alongside their associated networks. Unlike
    the other objects, delegations are not given a handle. They are searched for within
    Whois using a delegation name, like 0.192.in-addr.arpa.
  version: 1.0.0
host: www.arin.net
basePath: /regrws/core/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /delegation:
    get:
      summary: Get Delegation
      description: This call will return a payload containing details about the Delegation
        specified in your URL
      operationId: getDelegation
      responses:
        200:
          description: OK
      tags:
      - delegation
definitions: []
x-collection-name: ARIN
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
---
swagger: "2.0"
info:
  title: Akamai API List Universal Live Streams
  description: List Universal Live Streams
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events/v2/{accountId}/streams/universallive:
    get:
      summary: List Universal Live Streams
      description: List Universal Live Streams
      operationId: eventsv2accountidstreamsuniversallivesortfieldsortorderlimitstartindex
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field to sort the result set, either description or hostname
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      responses:
        200:
          description: OK
      tags:
      - events
      - account
      - streams
      - universallive
      - sortfield
      - sortorder
      - limit
      - startindex
definitions: []
x-collection-name: Akamai
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
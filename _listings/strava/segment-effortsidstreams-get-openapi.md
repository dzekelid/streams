---
swagger: "2.0"
x-collection-name: Strava
x-complete: 0
info:
  title: Strava Get segment effort streams
  description: Returns a set of streams for a segment effort completed by the authenticated
    athlete.
  version: 1.0.0
host: www.strava.com
basePath: /api/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activities/{id}/streams:
    get:
      summary: Get Activity Streams
      description: Returns the given activity's streams.
      operationId: getActivityStreams
      x-api-path-slug: activitiesidstreams-get
      parameters:
      - in: path
        name: id
        description: The identifier of the activity
      - in: query
        name: keys
        description: Desired stream types
      - in: query
        name: key_by_type
        description: Must be true
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Activity
      - Streams
  /segment_efforts/{id}/streams:
    get:
      summary: Get segment effort streams
      description: Returns a set of streams for a segment effort completed by the
        authenticated athlete.
      operationId: getSegmentEffortStreams
      x-api-path-slug: segment-effortsidstreams-get
      parameters:
      - in: path
        name: id
        description: The identifier of the segment effort
      - in: query
        name: keys
        description: The types of streams to return
      - in: query
        name: key_by_type
        description: Must be true
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Segment
      - Effort
      - Streams
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
swagger: "2.0"
x-collection-name: Strava
x-complete: 1
info:
  title: Strava API v3
  description: strava-api
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
  /segments/{id}/streams:
    get:
      summary: Get Segment Streams
      description: Returns the given segment's streams.
      operationId: getSegmentStreams
      x-api-path-slug: segmentsidstreams-get
      parameters:
      - in: path
        name: id
        description: The identifier of the segment
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
      - Streams
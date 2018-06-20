---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Add Livestreams
  description: Creates a video stream. The stream enables you to send your video to
    YouTube, which can then broadcast the video to your audience.
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /liveStreams:
    delete:
      summary: Delete Livestreams
      description: Deletes a video stream.
      operationId: deleteLivestreams
      x-api-path-slug: livestreams-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube live stream ID for the
          resource that is being deleted
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      responses:
        200:
          description: OK
      tags:
      - Livestreams
    get:
      summary: Get Livestreams
      description: Returns a list of video streams that match the API request parameters.
      operationId: getLivestreams
      x-api-path-slug: livestreams-get
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of YouTube
          stream IDs that identify the streams being retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: mine
        description: The mine parameter can be used to instruct the API to only return
          streams owned by the authenticated user
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more liveStream resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Livestreams
    post:
      summary: Add Livestreams
      description: Creates a video stream. The stream enables you to send your video
        to YouTube, which can then broadcast the video to your audience.
      operationId: postLivestreams
      x-api-path-slug: livestreams-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Livestreams
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
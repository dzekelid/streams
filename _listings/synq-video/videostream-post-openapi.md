---
swagger: "2.0"
x-collection-name: SYNQ Video
x-complete: 0
info:
  title: SYNQ Video Returns urls for streaming.
  description: Returns a stream url that you can stream to from your broadcasting
    software, and a playback url people can use to watch the stream.
  version: 1.9.1
host: api.synq.fm
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /video/stream:
    post:
      summary: Returns urls for streaming.
      description: Returns a stream url that you can stream to from your broadcasting
        software, and a playback url people can use to watch the stream.
      operationId: stream
      x-api-path-slug: videostream-post
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: video_id
        description: The ID of the video you want to stream to
      responses:
        200:
          description: OK
      tags:
      - Video
      - Stream
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
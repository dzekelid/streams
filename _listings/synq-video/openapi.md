swagger: "2.0"
x-collection-name: SYNQ Video
x-complete: 1
info:
  title: SYNQ Video
  description: -sign-up-for-a-developer-api-keyhttpswww-synq-fmregister-synq-api-guide
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
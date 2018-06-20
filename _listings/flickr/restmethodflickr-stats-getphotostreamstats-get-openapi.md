---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Stats Get Photostream Stats
  description: Get the number of views on a user's photostream for a given date.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.stats.getPhotostreamStats:
    get:
      summary: Stats Get Photostream Stats
      description: Get the number of views on a user's photostream for a given date.
      operationId: getRestMethodFlickr.stats.getphotostreamstats
      x-api-path-slug: restmethodflickr-stats-getphotostreamstats-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: date
        description: Stats will be returned for this date
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Stats
      - GetPhotostreamStats
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
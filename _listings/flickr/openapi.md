---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
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
---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 1
info:
  title: Books
  description: searches-for-books-and-manages-your-google-books-library-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /personalizedstream/get:
    get:
      summary: Get Stream
      description: Returns a stream of personalized book clusters
      operationId: books.personalizedstream.get
      x-api-path-slug: personalizedstreamget-get
      parameters:
      - in: query
        name: locale
        description: ISO-639-1 language and ISO-3166-1 country code
      - in: query
        name: maxAllowedMaturityRating
        description: The maximum allowed maturity rating of returned recommendations
      - in: query
        name: source
        description: String to identify the originator of this request
      responses:
        200:
          description: OK
      tags:
      - Stream
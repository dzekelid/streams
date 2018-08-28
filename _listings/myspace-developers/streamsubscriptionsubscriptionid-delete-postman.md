{
  "info": {
    "name": "My Space Delete Stream Subscription Subscriptionid",
    "_postman_id": "b3817676-3f6e-4508-87f5-89ceb1632a36",
    "description": "Deletes a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Statusmoodcomments",
      "item": [
        {
          "id": "6cda689c-5608-477a-8a62-894db2600ba6",
          "name": "1.0.statusmoodcomments.personId._self.statusId.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmoodcomments/:personId/@self/:statusId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "selector",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "statusId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posts a comment to a status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86946e10-3307-406f-a434-9934c3dc755a"
            }
          ]
        }
      ]
    },
    {
      "name": "Statusmood",
      "item": [
        {
          "id": "c4ce292d-3200-4f2f-987a-131103d26509",
          "name": "1.0.statusmood.personId.selector.friendId.history.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/:friendId/history"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "friendId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns History Friend."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f69e0f0e-c60a-4d9e-aeb8-546353992b58"
            }
          ]
        },
        {
          "id": "ef5f6f75-bce8-4b95-8f37-fa5846ac6b30",
          "name": "1.0.statusmood.personId.selector.friendId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/:friendId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "friendId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a status for Friend."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64fe591c-103a-40e5-9a9c-57648f6cc772"
            }
          ]
        },
        {
          "id": "7a25e1b9-df0d-49b4-8d4b-053d94afc8a3",
          "name": "1.0.statusmood.personId.selector.history.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/history"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns History User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fd3252f-b4f7-425c-951c-2e996a1ebb34"
            }
          ]
        },
        {
          "id": "69b9f552-ae81-4f76-baa7-904e45e90b2d",
          "name": "1.0.statusmood.personId.selector.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a status for User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a407781d-b167-4d3a-a122-702cccb80d6a"
            }
          ]
        },
        {
          "id": "2172b6de-2490-4ba0-a1e5-d4e7f02fb819",
          "name": "1.0.statusmood.personId.selector.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a status for User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78128442-4afd-47fe-b768-44a11339b93e"
            }
          ]
        },
        {
          "id": "b57ff2ba-7af6-428f-894e-d91c09b9f427",
          "name": "1.0.statusmood.personId._supportedMood.moodId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood/:moodId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "moodId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89772618-e60a-4004-959c-4f61424d0792"
            }
          ]
        },
        {
          "id": "d88ca646-ded8-4883-b8e3-df681dcb2af5",
          "name": "1.0.statusmood.personId._supportedMood.moodId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood/:moodId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "moodId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "787dcda8-2003-4da6-8049-4d520f0b8631"
            }
          ]
        },
        {
          "id": "d97d50d4-4699-413d-82b6-8f07c407983b",
          "name": "1.0.statusmood.personId._supportedMood.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported moods."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c5fa909-d222-49ff-97aa-b7974ba21c75"
            }
          ]
        },
        {
          "id": "f4beecd7-70f4-4e97-a66f-4dd8858441e3",
          "name": "1.0.statusmood.personId._supportedMood.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98f1d66b-94ca-465a-bc35-ff288d128e49"
            }
          ]
        }
      ]
    },
    {
      "name": "Mediaitemcomments",
      "item": [
        {
          "id": "fc12f166-3861-481f-b66f-28258c6db703",
          "name": "1.0.mediaitemcomments.personId._self.albumId.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaitemcomments/:personId/@self/:albumId/:mediaItemId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves item comments from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "425264ee-9c6d-491c-81b9-f10e887cbe99"
            }
          ]
        }
      ]
    },
    {
      "name": "MediaItems",
      "item": [
        {
          "id": "f0eac261-675e-485b-9b2f-40277bc8667c",
          "name": "1.0.mediaItems.personId._videos._supportedcategories.categoryId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@videos/@supportedcategories/:categoryId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "categoryId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves videos for Category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84c7e1ea-955f-449f-8049-e799aa15e335"
            }
          ]
        },
        {
          "id": "4a307ec2-1f77-4d0b-9960-1a87ae1b41d6",
          "name": "1.0.mediaItems.personId._videos._supportedcategories.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@videos/@supportedcategories"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves supported categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d44752e6-8c92-43cb-8cd8-7970c9c4b9c3"
            }
          ]
        },
        {
          "id": "a1186099-3598-4d87-abdd-48528779c08f",
          "name": "1.0.mediaItems.personId._self._videos.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos/:mediaItemId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "mediaItemId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a video."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a394660-e42e-4f3d-80ff-43f474bd815a"
            }
          ]
        },
        {
          "id": "33603e37-e484-401b-8a7a-b92e6a128ec0",
          "name": "1.0.mediaItems.personId._self._videos.mediaItemId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos/:mediaItemId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "mediaItemId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates an video."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bfc2155-f185-46a9-b227-b67f14f235f0"
            }
          ]
        },
        {
          "id": "8f06129b-684b-4d1f-bb16-30bd6ed0f9cc",
          "name": "1.0.mediaItems.personId._self._videos.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all the videos."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad80f82f-e486-4ec2-be60-82c08839a750"
            }
          ]
        },
        {
          "id": "9dd16f66-5ca5-4e60-8a82-b6269ea0fe1f",
          "name": "1.0.mediaItems.personId._self._videos.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds videos from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a4e7263-5450-47df-8230-6aae3d2c92dc"
            }
          ]
        },
        {
          "id": "c66d1bfb-ad75-498c-a5fd-fb9264a5fce4",
          "name": "1.0.mediaItems.personId._self.albumId.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId/:mediaItemId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves an item from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc58c2d3-8baf-4529-9700-72c405ee1f9a"
            }
          ]
        },
        {
          "id": "3a63e5ee-71f6-4e42-9c24-f495d87b0634",
          "name": "1.0.mediaItems.personId._self.albumId.mediaItemId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId/:mediaItemId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates an item from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca445e42-59f3-4a45-847e-41ac8b158b6b"
            }
          ]
        },
        {
          "id": "ff6495e9-7e4c-4376-8c29-cb810119ac59",
          "name": "1.0.mediaItems.personId._self.albumId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves items from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e6991ef-1afe-445d-bf4f-b74b6a0a6c33"
            }
          ]
        },
        {
          "id": "681d5a3c-3184-4565-a9c5-eccb4c71eb4e",
          "name": "1.0.mediaItems.personId._self.albumId.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds items from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5296dce-7418-48a9-94ca-967929b2566d"
            }
          ]
        },
        {
          "id": "1d992271-1ba6-4d6d-9519-9c0196e32786",
          "name": "1.0.mediaItems._supportedFields.get",
          "request": {
            "url": "http://api.myspace.com/1.0/mediaItems/@supportedFields?count=%7B%7D&fields=%7B%7D&format=%7B%7D&msPrivacyLevel=%7B%7D&startIndex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported fields."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc100f5a-b803-4a27-a28f-985a0cf61e82"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "fe03cc56-c965-4aad-96e5-8502c82472a2",
          "name": "stream.subscription._all.get",
          "request": {
            "url": "http://api.myspace.com/stream/subscription/@all?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all subscriptions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ad5321e-f2d7-4c6a-bb09-5a24b340597c"
            }
          ]
        },
        {
          "id": "675f6e71-b47a-4494-b9bb-405626bacea8",
          "name": "stream.subscription._all.delete",
          "request": {
            "url": "http://api.myspace.com/stream/subscription/@all?format=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes all subscriptions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b22278b-ea81-4717-a068-f9d36a81675d"
            }
          ]
        },
        {
          "id": "30813ab6-ec1d-4d29-902f-0393f874d596",
          "name": "stream.subscription.subscriptionId.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "stream/subscription/:subscriptionId"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a subscription."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d90dc51-a751-475a-b4e2-6fe98d6895a9"
            }
          ]
        }
      ]
    }
  ]
}
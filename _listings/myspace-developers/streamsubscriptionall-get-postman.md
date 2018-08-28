{
  "info": {
    "name": "My Space Get Stream Subscription All",
    "_postman_id": "5128dcc7-7b8c-42c3-a720-40292cc83861",
    "description": "Retrieves all subscriptions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Statusmoodcomments",
      "item": [
        {
          "id": "1b561e0d-efe2-44ab-b8d9-155007ec1af5",
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
              "id": "d1c92f08-c999-4082-8785-f80dba04046f"
            }
          ]
        }
      ]
    },
    {
      "name": "Statusmood",
      "item": [
        {
          "id": "0e0b64ce-4da3-46fe-bd39-e77132c50223",
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
              "id": "54f2e76e-0b47-4631-9110-3a370c3191e9"
            }
          ]
        },
        {
          "id": "e1a7f631-9956-4efe-a8ae-32a402d459da",
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
              "id": "d68a390a-e57c-476d-8440-9d9123cd22fa"
            }
          ]
        },
        {
          "id": "831ac495-df8f-4aef-aab6-cfd7c28c1014",
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
              "id": "3b3fc153-e0fb-4fc0-9983-30145ac7acec"
            }
          ]
        },
        {
          "id": "f29f68fb-36d7-4983-a2e5-15ee9777d712",
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
              "id": "208e3175-4e2f-4d34-9b17-0a4f1c04a6e5"
            }
          ]
        },
        {
          "id": "62243417-ff56-4c19-a258-d7bde462cd6c",
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
              "id": "686d3f0d-32c7-4af4-b356-4178f10a4a3b"
            }
          ]
        },
        {
          "id": "4fc4f9d5-52f0-41f8-af3d-a87703b54fd1",
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
              "id": "3ed536df-2c9b-414b-b05c-b1991bf82d39"
            }
          ]
        },
        {
          "id": "e45822ac-0772-4c27-b6da-22b15cd8a3ec",
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
              "id": "ecfdc57a-3559-4092-9a41-fc7e593ce73c"
            }
          ]
        },
        {
          "id": "1bce3e77-1c21-437b-9f1d-6dea1bdf1fec",
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
              "id": "b4f936dd-411d-49ad-a9e5-b1b0605f8fb8"
            }
          ]
        },
        {
          "id": "b2baa991-b1f0-4734-8a5c-11db458c7e2e",
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
              "id": "23c92daf-3299-42d0-b24f-77e9c3d085a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Mediaitemcomments",
      "item": [
        {
          "id": "79af9394-c122-43b9-8fdd-c0985860457e",
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
              "id": "02554329-4816-4354-a51e-d3dd7dd1287d"
            }
          ]
        }
      ]
    },
    {
      "name": "MediaItems",
      "item": [
        {
          "id": "c23d7d45-c91b-4b53-b84a-e36593c17aea",
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
              "id": "5a827474-2496-471a-a7e5-58e1206736d5"
            }
          ]
        },
        {
          "id": "62dbd70b-7c0d-43d7-ba37-59c279e632bd",
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
              "id": "88de5d6c-b693-402d-b9f2-2d84fa3db475"
            }
          ]
        },
        {
          "id": "3479c1a5-0807-4e98-a84a-2acdd1bcf109",
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
              "id": "b64752df-047c-423c-9728-c3c4901d9a92"
            }
          ]
        },
        {
          "id": "75797e3c-4c03-4348-9f73-a38e557e41bc",
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
              "id": "32be855d-ea94-4989-b417-bd5403adcf28"
            }
          ]
        },
        {
          "id": "6e5233b3-cb2a-49fe-a420-dd071e311c04",
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
              "id": "244faae3-5d68-4e34-9a0f-be92720b0961"
            }
          ]
        },
        {
          "id": "95851336-e7cc-49cf-a773-92f47ae14e09",
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
              "id": "60ab5437-1943-49cd-8e53-d285accf9a8f"
            }
          ]
        },
        {
          "id": "9664c812-ba72-4a73-b3e1-79e1ab2b2575",
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
              "id": "43c8e788-2429-4bf3-9d84-dae43edfb186"
            }
          ]
        },
        {
          "id": "7bd95f54-df5e-4bcf-b322-9a8e819c0a5d",
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
              "id": "c25e1c9b-fd57-4c6b-965d-8e7294a66f63"
            }
          ]
        },
        {
          "id": "f429a37a-6a81-403c-bb65-4b278291b366",
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
              "id": "6eca2882-642b-4100-956c-a336c5a693d6"
            }
          ]
        },
        {
          "id": "57315eb2-4839-4ef5-980c-a8a8f69808d3",
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
              "id": "c8cedaed-0766-4e0e-8822-a5e4085ad8cf"
            }
          ]
        },
        {
          "id": "953d350c-2a17-47a9-b9a5-6d79d3bd3ce2",
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
              "id": "2c0c8f81-4931-4ae0-bd4d-05d5906dc897"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "2e34d7ea-3f6e-407f-99f3-a6e982001457",
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
              "id": "a9afc1c6-24eb-43fa-9f19-bbab4f237bf9"
            }
          ]
        },
        {
          "id": "bf1e70cb-d835-4a8f-ad67-96b5152e965f",
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
              "id": "e141ed76-a884-4a24-998c-9fc5d392e0ad"
            }
          ]
        }
      ]
    }
  ]
}
swagger: "2.0"
x-collection-name: AWS DynamoDB
x-complete: 1
info:
  title: AWS DynamoDB API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateTable:
    get:
      summary: Update Table
      description: Modifies the provisioned throughput settings, global secondary
        indexes, or DynamoDB Streams settings for a given table.
      operationId: updateTable
      x-api-path-slug: actionupdatetable-get
      parameters:
      - in: query
        name: AttributeDefinitions
        description: An array of attributes that describe the key schema for the table
          and indexes
        type: string
      - in: query
        name: GlobalSecondaryIndexUpdates
        description: An array of one or more global secondary indexes for the table
        type: string
      - in: query
        name: ProvisionedThroughput
        description: The new provisioned throughput settings for the specified table
          or index
        type: string
      - in: query
        name: StreamSpecification
        description: Represents the DynamoDB Streams configuration for the table
        type: string
      - in: query
        name: TableName
        description: The name of the table to be updated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
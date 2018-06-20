---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 1
info:
  title: AutomationManagementClient
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft/testJob/streams/{jobStreamId}
  : get:
      summary: Test Job Streams Get
      description: Retrieve a test job streams identified by runbook name and stream
        id.
      operationId: TestJobStreams_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreamsjobstreamid-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: jobStreamId
        description: The job stream id
      - in: query
        name: No Name
      - in: path
        name: runbookName
        description: The runbook name
      responses:
        200:
          description: OK
      tags:
      - Test
      - Job
      - Streams
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft/testJob/streams
  : get:
      summary: Test Job Streams List By Test Job
      description: Retrieve a list of test job streams identified by runbook name.
      operationId: TestJobStreams_ListByTestJob
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreams-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: runbookName
        description: The runbook name
      responses:
        200:
          description: OK
      tags:
      - Test
      - Job
      - Streams
      - ListTest
      - Job
---
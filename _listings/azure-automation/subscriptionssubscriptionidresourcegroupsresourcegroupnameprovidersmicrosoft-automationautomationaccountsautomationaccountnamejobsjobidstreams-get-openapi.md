---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Job Stream List By Job
  version: 1.0.0
  description: Retrieve a list of jobs streams identified by job id.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/compilationjobs/{jobId}/streams/{jobStreamId}
  : get:
      summary: Dsc Compilation Job Get Stream
      description: Retrieve the job stream identified by job stream id.
      operationId: DscCompilationJob_GetStream
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamecompilationjobsjobidstreamsjobstreamid-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: jobId
        description: The job id
      - in: path
        name: jobStreamId
        description: The job stream id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Dsc
      - Compilation
      - Job
      - ""
      - Stream
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/jobs/{jobId}/streams/{jobStreamId}
  : get:
      summary: Job Stream Get
      description: Retrieve the job stream identified by job stream id.
      operationId: JobStream_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobsjobidstreamsjobstreamid-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: jobId
        description: The job id
      - in: path
        name: jobStreamId
        description: The job stream id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Job
      - Stream
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/jobs/{jobId}/streams
  : get:
      summary: Job Stream List By Job
      description: Retrieve a list of jobs streams identified by job id.
      operationId: JobStream_ListByJob
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobsjobidstreams-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: jobId
        description: The job Id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Job
      - Stream
      - ListJob
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
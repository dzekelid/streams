---
name: Azure Automation
x-slug: azure-automation
description: Automate all of those frequent, time-consuming, and error-prone cloud
  management tasks. Azure Automation helps you focus on work that adds business value.
  By reducing errors and boosting efficiency, it also helps to lower your operational
  costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Streams
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Automation API Test Job Streams Get
  x-api-slug: azure-automation-api
  description: Retrieve a test job streams identified by runbook name and stream id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft/testJob/streams/{jobStreamId}
  tags: Test, Job, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreamsjobstreamid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreamsjobstreamid-get-openapi.md
- name: Azure Automation API Test Job Streams List By Test Job
  x-api-slug: azure-automation-api
  description: Retrieve a list of test job streams identified by runbook name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft/testJob/streams
  tags: Test, Job, Streams, ListTest, Job
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedrafttestjobstreams-get-openapi.md
- name: Azure Automation API
  x-api-slug: azure-automation-api
  description: Automate all of those frequent, time-consuming, and error-prone cloud
    management tasks. Azure Automation helps you focus on work that adds business
    value. By reducing errors and boosting efficiency, it also helps to lower your
    operational costs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/azure-automation/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/automation/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/automation/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/automation/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/automation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
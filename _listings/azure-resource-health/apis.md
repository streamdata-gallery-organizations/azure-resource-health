---
name: Azure Resource Health
x-slug: azure-resource-health
description: Resource health helps you diagnose and get support when an Azure issue
  impacts your resources. It informs you about the current and past health of your
  resources and helps you mitigate issues. Resource health provides technical support
  when you need help with Azure service issues.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Resource Health
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Resource Health API Availability Statuses List By Subscription Id
  x-api-slug: azure-resource-health-api
  description: Lists the current availability status for all the resources in the
    subscription. Use the nextLink property in the response to get the next page of
    availability statuses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ResourceHealth/availabilityStatuses
  tags: Availability Statuses Subscription Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidprovidersmicrosoftresourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidprovidersmicrosoftresourcehealthavailabilitystatuses-get-openapi.md
- name: Azure Resource Health API Availability Statuses List By Resource Group
  x-api-slug: azure-resource-health-api
  description: Lists the current availability status for all the resources in the
    resource group. Use the nextLink property in the response to get the next page
    of availability statuses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ResourceHealth/availabilityStatuses
  tags: Availability Statuses Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftresourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftresourcehealthavailabilitystatuses-get-openapi.md
- name: Azure Resource Health API Availability Statuses Get By Resource
  x-api-slug: azure-resource-health-api
  description: Gets current availability status for a single resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////{resourceUri}/providers/Microsoft.ResourceHealth/availabilityStatuses/current
  tags: Availability Statuses Resource
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoftresourcehealthavailabilitystatusescurrent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoftresourcehealthavailabilitystatusescurrent-get-openapi.md
- name: Azure Resource Health API Availability Statuses List
  x-api-slug: azure-resource-health-api
  description: Lists the historical availability statuses for a single resource. Use
    the nextLink property in the response to get the next page of availability status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////{resourceUri}/providers/Microsoft.ResourceHealth/availabilityStatuses
  tags: Availability Statuses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoftresourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoftresourcehealthavailabilitystatuses-get-openapi.md
- name: Azure Resource Health API Operations List
  x-api-slug: azure-resource-health-api
  description: Lists available operations for the resourcehealth resource provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////providers/Microsoft.ResourceHealth/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/providersmicrosoftresourcehealthoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/providersmicrosoftresourcehealthoperations-get-openapi.md
- name: Azure Resource Health API
  x-api-slug: azure-resource-health-api
  description: Resource health helps you diagnose and get support when an Azure issue
    impacts your resources. It informs you about the current and past health of your
    resources and helps you mitigate issues. Resource health provides technical support
    when you need help with Azure service issues.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Azure Resource Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/openapi.md
x-common:
- type: x-faq
  url: https://docs.microsoft.com/en-us/azure/resource-health/resource-health-faq
- type: x-website
  url: https://docs.microsoft.com/en-us/azure/resource-health/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
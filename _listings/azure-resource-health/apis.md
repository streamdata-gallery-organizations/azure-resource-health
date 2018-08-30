---
name: Azure Resource Health
x-slug: azure-resource-health
description: Resource health helps you diagnose and get support when an Azure issue
  impacts your resources. It informs you about the current and past health of your
  resources and helps you mitigate issues. Resource health provides technical support
  when you need help with Azure service issues.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Resource Health
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft.ResourceHealth - Availability Statuses List By Subscription Id
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-resourcehealthavailabilitystatuses-get
  description: Lists the current availability status for all the resources in the
    subscription. Use the nextLink property in the response to get the next page of
    availability statuses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidprovidersmicrosoft-resourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidprovidersmicrosoft-resourcehealthavailabilitystatuses-get-openapi.md
- name: Microsoft.ResourceHealth - Availability Statuses List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcehealthavailabilitystatuses-get
  description: Lists the current availability status for all the resources in the
    resource group. Use the nextLink property in the response to get the next page
    of availability statuses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcehealthavailabilitystatuses-get-openapi.md
- name: Microsoft.ResourceHealth - Availability Statuses Get By Resource
  x-api-slug: resourceuriprovidersmicrosoft-resourcehealthavailabilitystatusescurrent-get
  description: Gets current availability status for a single resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoft-resourcehealthavailabilitystatusescurrent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoft-resourcehealthavailabilitystatusescurrent-get-openapi.md
- name: Microsoft.ResourceHealth - Availability Statuses List
  x-api-slug: resourceuriprovidersmicrosoft-resourcehealthavailabilitystatuses-get
  description: Lists the historical availability statuses for a single resource. Use
    the nextLink property in the response to get the next page of availability status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoft-resourcehealthavailabilitystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/resourceuriprovidersmicrosoft-resourcehealthavailabilitystatuses-get-openapi.md
- name: Microsoft.ResourceHealth - Operations List
  x-api-slug: providersmicrosoft-resourcehealthoperations-get
  description: Lists available operations for the resourcehealth resource provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-resource-health/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.redis.cache.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.resource.health.stack.network
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
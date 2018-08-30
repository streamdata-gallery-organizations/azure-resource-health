---
swagger: "2.0"
x-collection-name: Azure Resource Health
x-complete: 0
info:
  title: Azure Resource Health API Operations List
  description: Lists available operations for the resourcehealth resource provider
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
  /subscriptions/{subscriptionId}/providers/Microsoft.ResourceHealth/availabilityStatuses:
    get:
      summary: Availability Statuses List By Subscription Id
      description: Lists the current availability status for all the resources in
        the subscription. Use the nextLink property in the response to get the next
        page of availability statuses.
      operationId: AvailabilityStatuses_ListBySubscriptionId
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftresourcehealthavailabilitystatuses-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Availability Statuses Subscription Id
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ResourceHealth/availabilityStatuses:
    get:
      summary: Availability Statuses List By Resource Group
      description: Lists the current availability status for all the resources in
        the resource group. Use the nextLink property in the response to get the next
        page of availability statuses.
      operationId: AvailabilityStatuses_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftresourcehealthavailabilitystatuses-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Availability Statuses Resource Group
  /{resourceUri}/providers/Microsoft.ResourceHealth/availabilityStatuses/current:
    get:
      summary: Availability Statuses Get By Resource
      description: Gets current availability status for a single resource
      operationId: AvailabilityStatuses_GetByResource
      x-api-path-slug: resourceuriprovidersmicrosoftresourcehealthavailabilitystatusescurrent-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceUri
        description: The fully qualified ID of the resource, including the resource
          name and resource type
      responses:
        200:
          description: OK
      tags:
      - Availability Statuses Resource
  /{resourceUri}/providers/Microsoft.ResourceHealth/availabilityStatuses:
    get:
      summary: Availability Statuses List
      description: Lists the historical availability statuses for a single resource.
        Use the nextLink property in the response to get the next page of availability
        status
      operationId: AvailabilityStatuses_List
      x-api-path-slug: resourceuriprovidersmicrosoftresourcehealthavailabilitystatuses-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceUri
        description: The fully qualified ID of the resource, including the resource
          name and resource type
      responses:
        200:
          description: OK
      tags:
      - Availability Statuses
  /providers/Microsoft.ResourceHealth/operations:
    get:
      summary: Operations List
      description: Lists available operations for the resourcehealth resource provider
      operationId: Operations_List
      x-api-path-slug: providersmicrosoftresourcehealthoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
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
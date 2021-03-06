swagger: "2.0"
x-collection-name: Azure Resource Health
x-complete: 1
info:
  title: Microsoft.ResourceHealth
  description: the-resource-health-client-
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-resourcehealthavailabilitystatuses-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcehealthavailabilitystatuses-get
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
      x-api-path-slug: resourceuriprovidersmicrosoft-resourcehealthavailabilitystatusescurrent-get
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
      x-api-path-slug: resourceuriprovidersmicrosoft-resourcehealthavailabilitystatuses-get
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
      x-api-path-slug: providersmicrosoft-resourcehealthoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
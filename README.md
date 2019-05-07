# ![LOGO](logo.png) Azure Log Analytics - Operations Management **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Log Analytics - Operations Management API (version 2015-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/operationsmanagement-OperationsManagement/2015-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:35+03:00

## API Description

Azure Log Analytics API reference for Solution.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available OperationsManagement Rest API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Retrieves the ManagementAssociations list for the subscription

> Retrieves the ManagementAssociations list.

*Tags:* `ManagementAssociation`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieves the ManagementConfigurations list for the subscription

> Retrieves the ManagementConfigurations list.

*Tags:* `ManagementConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieves the solution list for the subscription

> Retrieves the solution list. It will retrieve both first party and third party solutions

*Tags:* `Solution`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Deletes the ManagementConfiguration

> Deletes the ManagementConfiguration in the subscription.

*Tags:* `ManagementConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `managementConfigurationName` - _required_ - User Management Configuration Name.
* `api-version` - _required_ - Client Api Version.

### Retrieve ManagementConfiguration.

> Retrieves the user ManagementConfiguration.

*Tags:* `ManagementConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `managementConfigurationName` - _required_ - User Management Configuration Name.
* `api-version` - _required_ - Client Api Version.

### Create/Update ManagementConfiguration.

> Creates or updates the ManagementConfiguration.

*Tags:* `ManagementConfiguration`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `api-version` - _required_ - Client Api Version.
* `managementConfigurationName` - _required_ - User Management Configuration Name.

### Retrieves the solution list for the subscription

> Retrieves the solution list. It will retrieve both first party and third party solutions

*Tags:* `Solution`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `api-version` - _required_ - Client Api Version.

### Deletes the solution

> Deletes the solution in the subscription.

*Tags:* `Solution`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `solutionName` - _required_ - User Solution Name.
* `api-version` - _required_ - Client Api Version.

### Retrieve solution.

> Retrieves the user solution.

*Tags:* `Solution`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `solutionName` - _required_ - User Solution Name.
* `api-version` - _required_ - Client Api Version.

### Create/Update Solution.

> Creates or updates the Solution.

*Tags:* `Solution`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `api-version` - _required_ - Client Api Version.
* `solutionName` - _required_ - User Solution Name.

### Deletes the ManagementAssociation

> Deletes the ManagementAssociation in the subscription.

*Tags:* `ManagementAssociation`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `providerName` - _required_ - Provider name for the parent resource.
* `resourceType` - _required_ - Resource type for the parent resource
* `resourceName` - _required_ - Parent resource name.
* `managementAssociationName` - _required_ - User ManagementAssociation Name.
* `api-version` - _required_ - Client Api Version.

### Retrieve ManagementAssociation.

> Retrieves the user ManagementAssociation.

*Tags:* `ManagementAssociation`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `providerName` - _required_ - Provider name for the parent resource.
* `resourceType` - _required_ - Resource type for the parent resource
* `resourceName` - _required_ - Parent resource name.
* `managementAssociationName` - _required_ - User ManagementAssociation Name.
* `api-version` - _required_ - Client Api Version.

### Create/Update ManagementAssociation.

> Creates or updates the ManagementAssociation.

*Tags:* `ManagementAssociation`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `api-version` - _required_ - Client Api Version.
* `providerName` - _required_ - Provider name for the parent resource.
* `resourceType` - _required_ - Resource type for the parent resource
* `resourceName` - _required_ - Parent resource name.
* `managementAssociationName` - _required_ - User ManagementAssociation Name.

## License

**flow**ground :- Telekom iPaaS / azure-com-operationsmanagement-operations-management-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

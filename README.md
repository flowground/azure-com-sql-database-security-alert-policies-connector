# ![LOGO](logo.png) Database Threat Detection Policy APIs **flow**ground Connector

## Description

A generated **flow**ground connector for the Database Threat Detection Policy APIs API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-databaseSecurityAlertPolicies/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:02+03:00

## API Description

Provides create, read and update functionality for database Threat Detection policies.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a database's threat detection policy.

*Tags:* `SecurityAlert`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which database Threat Detection policy is defined.
* `securityAlertPolicyName` - _required_ - The name of the security alert policy.
    Possible values: default.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a database's threat detection policy.

*Tags:* `SecurityAlert`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which database Threat Detection policy is defined.
* `securityAlertPolicyName` - _required_ - The name of the security alert policy.
    Possible values: default.
* `api-version` - _required_ - The API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-database-security-alert-policies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

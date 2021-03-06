# ![LOGO](logo.png) ApiManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApiManagementClient API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/apimanagement-apimtagresources/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:16+03:00

## API Description

Use these REST APIs for querying APIs. Operations and Products by tags in your Azure API Management deployment.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a collection of resources associated with tags.

*Tags:* `TagResource`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `$filter` - _optional_ - | Field       | Supported operators    | Supported functions               |
|-------------|------------------------|-----------------------------------|

|aid | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|name | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|displayName | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|apiName | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|apiRevision | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|path | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|description | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|serviceUrl | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|method | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|urlTemplate | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|terms | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith|
|state | eq |    |
|isCurrent | eq |    |

* `$top` - _optional_ - Number of records to return.
* `$skip` - _optional_ - Number of records to skip.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-apimanagement-apimtagresources-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

# ![LOGO](logo.png) AzureStack Azure Bridge Client **flow**ground Connector

## Description

A generated **flow**ground connector for the AzureStack Azure Bridge Client API (version 2017-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azurestack-Product/2017-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:38+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of products.

*Tags:* `Product`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `api-version` - _required_ - Client API Version.

### Returns the specified product.

*Tags:* `Product`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `productName` - _required_ - Name of the product.
* `api-version` - _required_ - Client API Version.

### Returns the extended properties of a product.

*Tags:* `Product`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroup` - _required_ - Name of the resource group.
* `registrationName` - _required_ - Name of the Azure Stack registration.
* `productName` - _required_ - Name of the product.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azurestack-product-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

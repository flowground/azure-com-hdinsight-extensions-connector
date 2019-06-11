# ![LOGO](logo.png) HDInsightManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the HDInsightManagementClient API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/hdinsight-extensions/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:59+03:00

## API Description

The HDInsight Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Disables the Operations Management Suite (OMS) on the HDInsight cluster.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `api-version` - _required_ - The HDInsight client API Version.

### Gets the status of Operations Management Suite (OMS) on the HDInsight cluster.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `api-version` - _required_ - The HDInsight client API Version.

### Enables the Operations Management Suite (OMS) on the HDInsight cluster.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `api-version` - _required_ - The HDInsight client API Version.

### Deletes the specified extension for HDInsight cluster.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `extensionName` - _required_ - The name of the cluster extension.
* `api-version` - _required_ - The HDInsight client API Version.

### Gets the extension properties for the specified HDInsight cluster extension.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `extensionName` - _required_ - The name of the cluster extension.
* `api-version` - _required_ - The HDInsight client API Version.

### Creates an HDInsight cluster extension.

*Tags:* `Extensions`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `extensionName` - _required_ - The name of the cluster extension.
* `api-version` - _required_ - The HDInsight client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-hdinsight-extensions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

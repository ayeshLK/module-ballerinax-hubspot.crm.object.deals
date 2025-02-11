## Hubspot Deal Creator

This use case demonstrates how the `hubspot.crm.object.deals` API can be utilized to create a Deal and update the state of the deal throgh the sales pipeline. The example involves a sequence of actions that leverage the Hubspot CRM API v3 to automate the process of creating and updating a sales pipeline

## Prerequisites

### 1. Setup the Hubspot developer account

Refer to the [Setup guide](https://github.com/ballerina-platform/module-ballerinax-hubspot.crm.object.deals/tree/main/examples/README.md#setup-guide) to obtain necessary credentials (client Id, client secret, Refresh tokens).

### 2. Configuration

Create a `Config.toml` file in the example's root directory and, provide your Hubspot account related configurations as follows:

```toml
clientId = "<Client ID>"
clientSecret = "<Client Secret>"
refreshToken = "<Access Token>"
```

## Run the example

Execute the following command to run the example:

```bash
bal run
```
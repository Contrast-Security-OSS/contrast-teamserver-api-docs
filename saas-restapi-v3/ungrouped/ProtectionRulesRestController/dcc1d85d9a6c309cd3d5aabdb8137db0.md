## /ng/{orgUuid}/protection/rules/env/{appUuid}/bulk (GET)
---
### Description
Retrieve multiple protection rule environment configurations
### Produces
application/json
### Consumes
application/json
### Path parameters
| Name | Description | Type | Required | Allowed Values |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| orgUuid |  | uuid | true |  |
| appUuid |  | uuid | true |  |
### Query Parameters
| Name | Description | Type | Required | Allowed Values |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| rules |  | set | true | String |
### Response status code
200 OK - OK
### Response object
[ProtectionRulesEnvConfigurationResponse](<../../objects/ProtectionRulesEnvConfigurationResponse.md>)

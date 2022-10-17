## /ng/{orgUuid}/applications/{appId}/breakdown/trace (GET)
---
### Visibility
PUBLIC
### Description
Get vulnerability breakdown for an application
### Auth
Roles: view,edit,rules_admin,admin
### Produces
application/json
### Consumes
application/json
### Headers
| Header Name | Description | Allowed Values |
| ----------- | ----------- | ----------- |
| API-Key | API key in plaintext |  |
| Authorization | Base64 encoded credentials of &quot;username:service-key&quot; |  |
### Path parameters
| Name | Description | Type | Required | Allowed Values |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| orgUuid | Organization UUID | organization | true | String |
| appId | Application ID | application | true | String |
### Query Parameters
| Name | Description | Type | Required | Allowed Values |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| includeMerged | Include merged applications | boolean | false | boolean |
| onlyOpenStatuses | Include Open Statuses in addition to status | boolean | false | boolean |
| status |  | set | false |  |
| appversion |  | string | false |  |
### Response status code
200 OK - OK
### Response object
[TraceBreakdownResponse](<../../objects/TraceBreakdownResponse.md>)

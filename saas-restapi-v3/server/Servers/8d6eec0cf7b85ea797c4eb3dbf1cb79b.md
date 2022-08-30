## /ng/{orgUuid}/servers/{serverId}/url/attack (GET)
---
### Visibility
PUBLIC
### Description
Get total number of attack urls for this server
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
| serverId | Server ID | server | true | Long |
### Query Parameters
| Name | Description | Type | Required | Allowed Values |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| interval | Date range | trendperiod | false | WEEK,MONTH,YEAR |
### Response status code
200 OK - OK
### Response object
URLServerResponse

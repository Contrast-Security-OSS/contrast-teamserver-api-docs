## /ng/{orgUuid}/traces/{traceUuid}/recommendation (GET)
---
### Visibility
PUBLIC
### Description
Get vulnerability recommendation from a vulnerability
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
| traceUuid | Vulnerability/Instance UUID | vulnerabilityandinstancekeyspair | true | String |
### Response status code
200 OK - OK
### Response object
[TraceRecommendationResponse](<../../objects/TraceRecommendationResponse.md>)

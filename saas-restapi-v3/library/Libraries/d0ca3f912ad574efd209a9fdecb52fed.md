## /ng/{orgUuid}/libraries/{appId}/status (PUT)
---
### Auth
Roles: admin
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
### Request Body
[LibraryUpdateStatusRequest](<../../objects/LibraryUpdateStatusRequest.md>)
### Response status code
200 OK - OK
### Response object
[BaseApiResponse](<../../objects/BaseApiResponse.md>)

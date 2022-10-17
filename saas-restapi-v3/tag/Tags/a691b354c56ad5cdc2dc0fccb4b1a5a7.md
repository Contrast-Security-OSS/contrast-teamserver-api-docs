## /ng/{orgUuid}/tags/libraries/bulk (PUT)
---
### Visibility
PUBLIC
### Description
Tag libraries bulk
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
### Request Body
[LibrariesTagsUpdateRequestNew](<../../objects/LibrariesTagsUpdateRequestNew.md>)
### Response status code
200 OK - OK
### Response object
[BaseApiResponse](<../../objects/BaseApiResponse.md>)

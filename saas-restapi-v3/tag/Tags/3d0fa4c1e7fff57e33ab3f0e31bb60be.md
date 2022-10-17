## /ng/{orgUuid}/tags/attacks/bulk (PUT)
---
### Visibility
PUBLIC
### Description
Tag attacks bulk
### Auth
Roles: edit,rules_admin,admin
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
[TagsAttacksUpdateRequest](<../../objects/TagsAttacksUpdateRequest.md>)
### Response status code
200 OK - OK
### Response object
[BaseApiResponse](<../../objects/BaseApiResponse.md>)

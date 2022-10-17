## OrganizationAccessGroupUsersResponse
---
### Description
EAC Organization Users Group Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| group | EAC Group Resource | AccessGroupResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"group":{"links":[],"users":[]},"messages":[],"success":true}
```

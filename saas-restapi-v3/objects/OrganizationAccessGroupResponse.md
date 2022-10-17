## OrganizationAccessGroupResponse
---
### Description
EAC Organization Group Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| group | EAC Group Resource | AccessGroupOrganizationResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"group":{"access_level":"","accounts":[],"app_role":"","applications":[],"group_id":0,"links":[],"name":"","onboard_role":"","readonly":true,"users":[]},"messages":[],"success":true}
```

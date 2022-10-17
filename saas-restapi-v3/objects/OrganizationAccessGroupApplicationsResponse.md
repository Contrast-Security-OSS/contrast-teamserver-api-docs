## OrganizationAccessGroupApplicationsResponse
---
### Description
EAC Organization Applications Group Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| group | EAC Group Resource | AccessGroupApplicationsResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"group":{"applications":[],"links":[]},"messages":[],"success":true}
```

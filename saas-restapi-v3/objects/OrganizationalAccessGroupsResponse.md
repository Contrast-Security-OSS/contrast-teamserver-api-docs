## OrganizationalAccessGroupsResponse
---
### Description
Organizational EAC Groups Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| custom_groups | List of Custom EAC Group Resource | OrganizationalAccessGroupResource |  | false |
| messages | List of messages | list |  | false |
| predefined_groups | List of Read only EAC Group Resource | OrganizationalAccessGroupResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"custom_groups":{"count":0,"groups":[]},"messages":[],"predefined_groups":{"count":0,"groups":[]},"success":true}
```

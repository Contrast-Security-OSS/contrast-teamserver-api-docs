## AccessGroupResource
---
### Description
EAC Group Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| access_level | Access level | accesscontrolgrouplevel |  | false |
| accounts | List of account roles | list |  | false |
| applications | List of all application that have access in this group | list |  | false |
| group_id | Group ID | long |  | false |
| is_onboarded_to_group | Whether Application access is onboarded to group | boolean |  | false |
| name | Group Name | string |  | false |
| readonly | Is group read-only | boolean |  | false |
| role | Role for all the applications | string |  | false |
| total_users | Number of users in this group | long |  | false |
### Template
```
{"access_level":"","accounts":[],"applications":[],"group_id":0,"is_onboarded_to_group":true,"links":[],"name":"","readonly":true,"role":"","total_users":0}
```

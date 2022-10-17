## AccessGroupOrganizationResource
---
### Description
EAC Group Organization Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| access_level | Access level | accesscontrolgrouplevel |  | false |
| accounts | List of account roles | list |  | false |
| app_role | Application role | string |  | false |
| applications | List of applications | list |  | false |
| group_id | Group id | long |  | false |
| name | Group Name | string |  | false |
| onboard_role | Onboard role | string |  | false |
| readonly | If the Group is Read-only | boolean |  | false |
| users | List of users | list |  | false |
### Template
```
{"access_level":"","accounts":[],"app_role":"","applications":[],"group_id":0,"links":[],"name":"","onboard_role":"","readonly":true,"users":[]}
```

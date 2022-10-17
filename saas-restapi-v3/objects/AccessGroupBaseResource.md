## AccessGroupBaseResource
---
### Description
EAC Group Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| access_level | Access level | accesscontrolgrouplevel |  | false |
| group_id | Group ID | long |  | false |
| name | Group Name | string |  | false |
| organizations | Set of organizations | set |  | false |
| readonly | Is group read-only | boolean |  | false |
### Template
```
{"access_level":"","group_id":0,"links":[],"name":"","organizations":[],"readonly":true}
```

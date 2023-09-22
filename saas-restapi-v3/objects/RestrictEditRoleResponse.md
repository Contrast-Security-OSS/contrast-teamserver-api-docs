## RestrictEditRoleResponse
---
### Description
Base API form Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| success | Indicates whether API response was successful or not | boolean |  | false |
| messages | List of messages | list |  | false |
| enabled | true if restricted edit role is allowed, false otherwise | boolean |  | false |
### Template
```
{"enabled":true,"messages":[],"success":true}
```

## AccessControlGroupRequest
---
### Description
Access Group Information
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| name | EAC Group Name | string |  | true |
| scope | Access Group scope | AccessControlScopeItem |  | true |
| users | List of users | list |  | true |
### Template
```
{"name":"","scope":{"account_scope":{"exceptions":[]},"app_scope":{"exceptions":[],"onboard_role":"","role":""}},"users":[]}
```

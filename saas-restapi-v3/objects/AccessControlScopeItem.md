## AccessControlScopeItem
---
### Description
EAC Scope Item
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| account_scope | EAC Account Item | BaseAccessAccountItem |  | false |
| app_scope | EAC Application Item | BaseAccessAppItem |  | true |
### Template
```
{"account_scope":{"exceptions":[]},"app_scope":{"exceptions":[],"onboard_role":"","role":""}}
```

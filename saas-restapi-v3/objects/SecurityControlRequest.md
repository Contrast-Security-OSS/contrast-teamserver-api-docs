## SecurityControlRequest
---
### Description
Security Control Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Apply to all applications | boolean |  | false |
| all_rules | Apply to All Rules | boolean |  | false |
| api | API | string |  | false |
| applications | Applications to apply security control | list |  | false |
| language | Language | string |  | false |
| name | Name | string |  | false |
| pattern | Pattern | string |  | false |
| rules | Rules to Apply Security Control | list |  | false |
### Template
```
{"all_applications":true,"all_rules":true,"api":"","applications":[],"language":"","name":"","pattern":"","rules":[]}
```

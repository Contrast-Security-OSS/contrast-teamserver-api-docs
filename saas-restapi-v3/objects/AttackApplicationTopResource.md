## AttackApplicationTopResource
---
### Description
Attack Application Top Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application | ApplicationBaseResource |  | false |
| attackLabel | Label | string |  | false |
| sources | List of Sources | list |  | false |
| status | Attack status | attackstatus |  | false |
### Template
```
{"application":{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0},"attackLabel":"","links":[],"sources":[],"status":""}
```

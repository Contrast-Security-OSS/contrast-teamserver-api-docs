## AlertAttackRequest
---
### Description
Alert Attack Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| allAppsEnabled | Is All Application Enabled | boolean |  | false |
| allUsers | Is All Users Enabled | boolean |  | false |
| apps | List of Application IDs | list |  | false |
| description | Description | string |  | true |
| name | Alert Attack Name | string |  | true |
| recipients | List of recipients | set |  | true |
| tags | List of application tags | list |  | false |
| triggers | List of triggers | list |  | true |
| url | URL | string |  | false |
### Template
```
{"allAppsEnabled":true,"allUsers":true,"apps":[],"description":"","name":"","recipients":[],"tags":[],"triggers":[],"url":""}
```

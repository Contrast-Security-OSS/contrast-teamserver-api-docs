## AlertRequest
---
### Description
Alert Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| allUsers | Is notification enabled for all Users? | boolean |  | false |
| apps | List of application Ids | list |  | false |
| conditions | List of conditions | list |  | true |
| description | Description | string |  | true |
| frequency | Frequency | string |  | true |
| name | Notification Name | string |  | true |
| recipients | List of recipients | list |  | true |
| tags | List of application tags | list |  | false |
### Template
```
{"allUsers":true,"apps":[],"conditions":[],"description":"","frequency":"","name":"","recipients":[],"tags":[]}
```

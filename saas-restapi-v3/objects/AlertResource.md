## AlertResource
---
### Description
Alert Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| alert_id | Alert ID | string |  | false |
| allAppsEnabled | Enable all applications | boolean |  | false |
| allUsers | Enable for all users | boolean |  | false |
| apps | List of applications | list |  | false |
| conditions | List of conditions | list |  | false |
| description | Description | string |  | false |
| enabled | Enabled | boolean |  | false |
| frequency | Frequency | string |  | false |
| last_send_time | Last send time | long |  | false |
| name | Alert Name | string |  | false |
| recipients | List of recipients | list |  | false |
| tags | List of application tags | collection |  | false |
| triggers | List of triggers | list |  | false |
| type | Alert type | alerttype |  | false |
| users | List of TeamServer users recipients | list |  | false |
### Template
```
{"frequency":"","alert_id":"","allAppsEnabled":true,"allUsers":true,"apps":[],"conditions":[],"description":"","enabled":true,"last_send_time":0,"links":[],"name":"","recipients":[],"tags":[],"triggers":[],"type":"","users":[]}
```

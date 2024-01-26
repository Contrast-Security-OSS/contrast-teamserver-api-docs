## AlertResource
---
### Description
Alert Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| alert_id | Alert id | string |  | false |
| allAppsEnabled | Enable all apps | boolean |  | false |
| allUsers | Enable for all users | boolean |  | false |
| apps | List of Application Alert Resources | list |  | false |
| conditions | List of conditions | list |  | false |
| description | Description | string |  | false |
| enabled | Enabled | boolean |  | false |
| frequency | Frequency | string |  | false |
| last_send_time | Last send time | long |  | false |
| name | Notification Name | string |  | false |
| recipients | List of recipients | list |  | false |
| tags | List of application tags | collection |  | false |
| type | Alert type | alerttype |  | false |
| users | List of TeamServer users recipients | list |  | false |
### Template
```
{"frequency":"","alert_id":"","allAppsEnabled":true,"allUsers":true,"apps":[],"conditions":[],"description":"","enabled":true,"last_send_time":0,"links":[],"name":"","recipients":[],"tags":[],"type":"","users":[]}
```

## AlertAttackResource
---
### Description
Alert Attack Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| alert_id | Alert ID | string |  | false |
| allAppsEnabled | Enable all apps | boolean |  | false |
| allUsers | Enable for all users | boolean |  | false |
| apps | List of Applications | list |  | false |
| description | Description | string |  | false |
| enabled | Enabled | boolean |  | false |
| last_send_time | Last send time | long |  | false |
| name | Alert Attack Name | string |  | false |
| tags | List of application tags | list |  | false |
| triggers | List of triggers | list |  | false |
| type | Alert type | alerttype |  | false |
| url | URL | string |  | false |
| users | List of TeamServer users recipients | list |  | false |
### Template
```
{"alert_id":"","allAppsEnabled":true,"allUsers":true,"apps":[],"description":"","enabled":true,"last_send_time":0,"links":[],"name":"","tags":[],"triggers":[],"type":"","url":"","users":[]}
```

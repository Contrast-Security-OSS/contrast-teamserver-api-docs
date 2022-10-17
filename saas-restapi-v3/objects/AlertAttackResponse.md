## AlertAttackResponse
---
### Description
Alert Attack Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| alert | Alert Resource | AlertAttackResource |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"alert":{"alert_id":"","allAppsEnabled":true,"allUsers":true,"apps":[],"description":"","enabled":true,"last_send_time":0,"links":[],"name":"","tags":[],"triggers":[],"type":"","url":"","users":[]},"errors":[],"messages":[],"success":true}
```

## AlertResponse
---
### Description
Alert Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| alert | Alert Resource | AlertResource |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"alert":{"frequency":"","alert_id":"","allUsers":true,"apps":[],"conditions":[],"description":"","enabled":true,"last_send_time":0,"links":[],"name":"","recipients":[],"tags":[],"type":"","users":[]},"errors":[],"messages":[],"success":true}
```

## RaspTargetedAppsResponse
---
### Description
RASP Targeted Apps Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| items | List of targeted applications | list |  | false |
| messages | List of messages | list |  | false |
| remaining_applications | List of remaining application names | list |  | false |
| remaining_breakdown | List of targeted applications | AttackMonitorTopApplicationResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total | Total number of events | long |  | false |
### Template
```
{"errors":[],"items":[],"messages":[],"remaining_applications":[],"remaining_breakdown":{"app_id":"","application":"","blocked_attacks":0,"exploited_attacks":0,"importance":"","probed_attacks":0,"suspicious_attacks":0,"total_attacks":0},"success":true,"total":0}
```

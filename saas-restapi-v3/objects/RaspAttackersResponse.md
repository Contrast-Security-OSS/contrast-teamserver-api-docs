## RaspAttackersResponse
---
### Description
RASP Event Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| items | List of top events | list |  | false |
| messages | List of messages | list |  | false |
| remaining_breakdown | List of targeted applications | AttackMonitorTopEventResource |  | false |
| remaining_events | Remaining Events | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total | Total Events | long |  | false |
### Template
```
{"errors":[],"items":[],"messages":[],"remaining_breakdown":{"blocked_attacks":0,"event":"","exploited_attacks":0,"probed_attacks":0,"rule_uuid":"","suspicious_attacks":0,"total_attacks":0},"remaining_events":[],"success":true,"total":0}
```

## AttackMonitorFilterResponse
---
### Description
RASP Attacker Monitor Timeline Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_events | Total number of events | int |  | false |
| total_requests | Total number of requests | int |  | false |
| trend_data | Trend Data | list |  | false |
### Template
```
{"errors":[],"messages":[],"success":true,"total_events":0,"total_requests":0,"trend_data":[]}
```

## RaspAttackersResponse
---
### Description
RASP Attackers Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attackers | List of top attackers | list |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| remaining_attackers | Remaining Attackers | list |  | false |
| remaining_breakdown | Remaining attackers breakdown | AttackMonitorTopAttackerResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total | Total number of attack events | long |  | false |
### Template
```
{"attackers":[],"errors":[],"messages":[],"remaining_attackers":[],"remaining_breakdown":{"attack_status":"","attack_types":[],"attack_uuids":[],"attacker":"","attackersItems":[],"blocked_attacks":0,"exploited_attacks":0,"probed_attacks":0,"source_ips":[],"source_name":"","suspicious_attacks":0,"total_attacks":0,"unknown":true},"success":true,"total":0}
```

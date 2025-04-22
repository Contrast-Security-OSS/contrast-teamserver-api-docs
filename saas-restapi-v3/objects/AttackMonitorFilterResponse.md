## AttackMonitorFilterResponse
---
### Description
RASP Attacker Monitor Filter Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applications | Application Names | list |  | false |
| attackers | List of attackers | collection |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| rule | Rule Names | list |  | false |
| rule_severities | Rule Severities | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"applications":[],"attackers":[],"errors":[],"messages":[],"rule_severities":[],"rule":[],"success":true}
```

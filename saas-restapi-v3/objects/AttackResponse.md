## AttackResponse
---
### Description
Attack Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attack | Attack Resource | AttackResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"attack":{"active":true,"application_importance":"","attack_duration":0,"id":0,"attack_impact":"","attack_label":"","uuid":"","attackers":[],"attacksApplication":[],"end_time":0,"first_event_time":0,"last_event_time":0,"links":[],"requests_per_second":0,"rules":[],"servers":[],"severity_code":"","source":"","source_name":"","start_time":0,"status":"","suppressed":true,"probes":0,"type":"","user_agents":[]},"messages":[],"success":true}
```

## AttackResource
---
### Description
Attack Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| active | Active | boolean |  | false |
| application_importance | Application importance | applicationimportance |  | false |
| attack_duration | Attack duration | long |  | false |
| attack_impact | Attack impact | attackimpact |  | false |
| attack_label | Label | string |  | false |
| attackers | List of attackers | list |  | false |
| attacksApplication | List of application attacks | list |  | false |
| end_time | End time | long |  | false |
| first_event_time | First event time | long |  | false |
| id | Attack ID | long |  | false |
| last_event_time | Last event time | long |  | false |
| probes | Total number of probes | long |  | false |
| requests_per_second | Requests per second | long |  | false |
| rules | List of rules | list |  | false |
| servers | List of servers | list |  | false |
| severity_code | Severity code | severitycode |  | false |
| source | Source | string |  | false |
| source_name | Associated source name | string |  | false |
| start_time | Start time | long |  | false |
| status | Attack status | attackstatus |  | false |
| suppressed | Suppressed | boolean |  | false |
| type | Attack type | attacktype |  | false |
| user_agents | List of user agents | set |  | false |
| uuid | Attack UUID | string |  | false |
### Template
```
{"active":true,"application_importance":"","attack_duration":0,"id":0,"attack_impact":"","attack_label":"","uuid":"","attackers":[],"attacksApplication":[],"end_time":0,"first_event_time":0,"last_event_time":0,"links":[],"requests_per_second":0,"rules":[],"servers":[],"severity_code":"","source":"","source_name":"","start_time":0,"status":"","suppressed":true,"probes":0,"type":"","user_agents":[]}
```

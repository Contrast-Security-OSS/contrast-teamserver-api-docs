## ApplicationAttackResource
---
### Description
Application Attack Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attack_label | Attack label | string |  | false |
| attackers | List of attackers | list |  | false |
| end_time | End time | long |  | false |
| rate | Attack rate | attackrate |  | false |
| servers | List of Server Resources | list |  | false |
| severity | Severity code | severitycode |  | false |
| source | IP Source | string |  | false |
| start_time | Start time | long |  | false |
| status | Attack status | attackstatus |  | false |
| type | Attack type | attacktype |  | false |
| uuid | Attack UUID | string |  | false |
| volume | Volume | long |  | false |
### Template
```
{"attack_label":"","uuid":"","attackers":[],"end_time":0,"links":[],"rate":"","servers":[],"severity":"","source":"","start_time":0,"status":"","type":"","volume":0}
```

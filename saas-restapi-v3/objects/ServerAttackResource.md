## ServerAttackResource
---
### Description
Server Attack Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application | ApplicationBaseResource |  | false |
| attack_label | Attack label | string |  | false |
| end_time | End time | long |  | false |
| rate | Attack rate | attackrate |  | false |
| severity | Severity code | severitycode |  | false |
| source | Source IP | string |  | false |
| start_time | Start time | long |  | false |
| status | Attack status | attackstatus |  | false |
| type | Attack type | attacktype |  | false |
| volume | Volume | long |  | false |
### Template
```
{"application":{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0},"attack_label":"","end_time":0,"links":[],"rate":"","severity":"","source":"","start_time":0,"status":"","type":"","volume":0}
```

## AttackApplicationResource
---
### Description
Attack Application Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application | ApplicationAttackInfoResource |  | false |
| attack_label | Label | string |  | false |
| end_time | End time | long |  | false |
| id | Attack application ID | long |  | false |
| last_event_time | Last event time | long |  | false |
| probes | Total number of probes | long |  | false |
| severity | Severity code | severitycode |  | false |
| start_time | Start time | long |  | false |
| status | Attack status | attackstatus |  | false |
| uuid | Attack application UUID | string |  | false |
### Template
```
{"application":{"context_path":"","app_id":"","language":"","app_license":{},"name":"","attack_status":"","child":true,"first_seen":0,"importance":0,"importance_description":"","last_seen":0,"license_level":"","links":[],"master":true,"metadataEntities":[],"organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"parent_app_id":"","primary":true,"roles":[],"servers":[],"status":"","total_modules":0},"id":0,"uuid":"","attack_label":"","end_time":0,"last_event_time":0,"links":[],"probes":0,"severity":"","start_time":0,"status":""}
```

## ApplicationAttackInfoResource
---
### Description
Application Attack Info Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_id | Application id | string |  | false |
| app_license | Application License | applicense |  | false |
| attack_status | Attack status | attackstatus |  | false |
| child | Is application child | boolean |  | false |
| context_path | Application context path | string |  | false |
| first_seen | Application first time seen | long |  | false |
| importance | Application Importance | integer |  | false |
| importance_description | Application Importance Description | applicationimportance |  | false |
| language | Application language | string |  | false |
| last_seen | Time last seen | long |  | false |
| license_level | License Level | servicelevel |  | false |
| master | Is application master | boolean |  | false |
| metadataEntities | List of metadata entities | list |  | false |
| name | Application name | string |  | false |
| organization | Organization Resource | OrganizationBaseResource |  | false |
| parent_app_id | Application parent ID | string |  | false |
| primary | Is application primary | boolean |  | false |
| roles | List of allowed roles | collection |  | false |
| servers | Application servers | list |  | false |
| status | Application status | string |  | false |
| total_modules | Number of app modules | long |  | false |
### Template
```
{"context_path":"","app_id":"","language":"","app_license":{},"name":"","attack_status":"","child":true,"first_seen":0,"importance":0,"importance_description":"","last_seen":0,"license_level":"","links":[],"master":true,"metadataEntities":[],"organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"parent_app_id":"","primary":true,"roles":[],"servers":[],"status":"","total_modules":0}
```

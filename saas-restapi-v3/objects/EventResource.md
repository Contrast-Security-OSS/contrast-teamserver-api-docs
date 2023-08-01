## EventResource
---
### Description
Event Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application Resource | ApplicationAttackInfoResource |  | false |
| attack_suppressed | Is attack suppressed? | boolean |  | false |
| attack_type | Type of attack | attacktype |  | false |
| attack_uuid | Attack UUID | string |  | false |
| attackers | List of attackers | list |  | false |
| callLocation | Call Location | string |  | false |
| details | Details | string |  | false |
| detectionType | Detection type | string |  | false |
| displayName | Display name | string |  | false |
| event_uuid | Event UUID | string |  | false |
| exclusion_created | Has this event an exclusion created | boolean |  | false |
| httpRequest | HTTP Request | attacksamplerequestview |  | false |
| received | Received | long |  | false |
| result | Activity rule type | attackstatus |  | false |
| rule | Rule name | string |  | false |
| rule_id | Rule Id | long |  | false |
| rule_uuid | Rule UUID is a string that uniquely identifies the RASP rule associated with this attack event | string |  | false |
| server | Server | ServerResource |  | false |
| source | Source IP | string |  | false |
| sourceName | Source Name details | SourceNameResource |  | false |
| source_name | Source Name | string |  | false |
| suppressed | Suppressed | boolean |  | false |
| tags | Tags | set |  | false |
| type | Type of attack event (rule, IP blacklist, etc.) | string |  | false |
| url | URL. Empty if this RASP did not occur in the context of an HTTP request | string |  | false |
| user_input | User input values | EventUserInputResource |  | false |
### Template
```
{"application":{"context_path":"","app_id":"","language":"","app_license":{},"name":"","attack_status":"","child":true,"first_seen":0,"importance":0,"importance_description":"","last_seen":0,"license_level":"","links":[],"master":true,"metadataEntities":[],"organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"parent_app_id":"","primary":true,"roles":[],"servers":[],"status":"","total_modules":0},"attack_suppressed":true,"attack_type":"","attack_uuid":"","attackers":[],"callLocation":"","details":"","detectionType":"","displayName":"","event_uuid":"","exclusion_created":true,"httpRequest":{},"links":[],"received":0,"result":"","rule":"","rule_id":0,"rule_uuid":"","server":{"num_apps":0,"applications":[],"assess":true,"assess_enable_location":"","assess_enable_property_name":"","assess_last_update":0,"assessPending":true,"assess_sensors":true,"is_assess_status_locked":true,"config_source_assess":"","config_source_protect":"","defend":true,"defendPending":true,"defend_sensors":true,"defense_last_update":0,"agent_version":"","environment":"","has_instrumentation_conflict":true,"hostname":"","language":"","last_activity":0,"last_startup":0,"latest_agent_version":"","license":{"end":0,"licensed":true,"links":[],"start":0},"links":[],"logEnhancerPending":true,"logLevel":"","logPath":"","name":"","noPending":true,"out_of_date":true,"protect_enable_location":"","protect_enable_property_name":"","is_protect_status_locked":true,"server_id":0,"path":"","type":"","status":"","syslog_enabled":true,"syslog_ip_address":"","tags":[]},"source":"","source_name":"","sourceName":{},"suppressed":true,"tags":[],"type":"","url":"","user_input":{"links":[],"name":"","omitted_value":true,"truncated_value":true,"type":"","value":""}}
```

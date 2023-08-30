## ServerResponse
---
### Description
Server Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| server | Server Resource | ServerResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"server":{"num_apps":0,"applications":[],"assess":true,"assess_enable_location":"","assess_enable_property_name":"","assess_last_update":0,"assessPending":true,"assess_sensors":true,"is_assess_status_locked":true,"config_source_assess":"","config_source_protect":"","defend":true,"defendPending":true,"defend_sensors":true,"defense_last_update":0,"diagnostic_collection_enabled":true,"agent_version":"","environment":"","has_instrumentation_conflict":true,"hostname":"","language":"","last_activity":0,"last_startup":0,"latest_agent_version":"","license":{"end":0,"licensed":true,"links":[],"start":0},"links":[],"logEnhancerPending":true,"logLevel":"","logPath":"","name":"","noPending":true,"out_of_date":true,"protect_enable_location":"","protect_enable_property_name":"","is_protect_status_locked":true,"server_id":0,"path":"","type":"","status":"","syslog_enabled":true,"syslog_ip_address":"","tags":[]},"success":true}
```

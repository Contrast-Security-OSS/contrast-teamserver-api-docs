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
{"messages":[],"server":{"num_apps":0,"applications":[],"assess":true,"assess_last_update":0,"assessPending":true,"assess_sensors":true,"config_source_assess":"","config_source_protect":"","defend":true,"defendPending":true,"defend_sensors":true,"defense_last_update":0,"agent_version":"","environment":"","has_instrumentation_conflict":true,"hostname":"","language":"","last_activity":0,"last_startup":0,"latest_agent_version":"","license":{"end":0,"licensed":true,"links":[],"start":0},"links":[],"logEnhancerPending":true,"logLevel":"","logPath":"","name":"","noPending":true,"out_of_date":true,"server_id":0,"path":"","type":"","should_block_assess_toggle":true,"should_block_protect_toggle":true,"status":"","syslog_enabled":true,"syslog_ip_address":"","tags":[]},"success":true}
```

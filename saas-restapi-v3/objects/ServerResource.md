## ServerResource
---
### Description
Server Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agent_version | Agent version | string |  | false |
| applications | List of applications | list |  | false |
| assess | Is server Assess | boolean |  | false |
| assessPending | Is server changing Assess on restart | boolean |  | false |
| assess_last_update | Last assess change time | long |  | false |
| assess_sensors | Are the assess sensors active | boolean |  | false |
| defend | Is server Defend | boolean |  | false |
| defendPending | Is server changing Defend on restart | boolean |  | false |
| defend_sensors | Are the defend sensors active | boolean |  | false |
| defense_last_update | Last defense change time | long |  | false |
| environment | Environment | serverenvironment |  | false |
| has_instrumentation_conflict | An specific app has an instrumentation conflict with this server | boolean |  | false |
| hostname | Hostname | string |  | false |
| language | Language | string |  | false |
| last_activity | Last activity time | long |  | false |
| last_startup | Last startup time | long |  | false |
| latest_agent_version | The latest available agent version | string |  | false |
| license | Protection license | ProtectionLicenseResource |  | false |
| logEnhancerPending | Is server changing Log Enhancers on restart | boolean |  | false |
| logLevel | Security Log Level | string |  | false |
| logPath | Log Path | string |  | false |
| name | Server name | string |  | false |
| noPending | Is server changing any settings on restart | boolean |  | false |
| num_apps | Number of applications on server | long |  | false |
| out_of_date | If the agent on this server is out of date | boolean |  | false |
| path | Server path | string |  | false |
| server_id | Server id | long |  | false |
| status | Status | serverstatus |  | false |
| syslog_enabled | Syslog enabled | boolean |  | false |
| syslog_ip_address | Syslog IP address | string |  | false |
| tags | List of tags | list |  | false |
| type | Server type | string |  | false |
### Template
```
{"num_apps":0,"applications":[],"assess":true,"assess_last_update":0,"assessPending":true,"assess_sensors":true,"defend":true,"defendPending":true,"defend_sensors":true,"defense_last_update":0,"agent_version":"","environment":"","has_instrumentation_conflict":true,"hostname":"","language":"","last_activity":0,"last_startup":0,"latest_agent_version":"","license":{"end":0,"licensed":true,"links":[],"start":0},"links":[],"logEnhancerPending":true,"logLevel":"","logPath":"","name":"","noPending":true,"out_of_date":true,"server_id":0,"path":"","type":"","status":"","syslog_enabled":true,"syslog_ip_address":"","tags":[]}
```

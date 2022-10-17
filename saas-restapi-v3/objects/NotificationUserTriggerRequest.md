## NotificationUserTriggerRequest
---
### Description
Notification User Trigger Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_asset_types | Select all rule severities | boolean |  | false |
| all_attack_status | Select all attack status | boolean |  | false |
| all_rule_severities | Select all rule severities | boolean |  | false |
| all_server_environments | Select all server environments | boolean |  | false |
| asset_type | Asset type | notificationassettype |  | false |
| attack_status | Attack Status | attackstatus |  | false |
| rule_severity | Rule Severity | ruleseverity |  | false |
| server_environment | Server environment | serverenvironment |  | false |
### Template
```
{"all_asset_types":true,"all_attack_status":true,"all_rule_severities":true,"all_server_environments":true,"asset_type":"","attack_status":"","rule_severity":"","server_environment":""}
```

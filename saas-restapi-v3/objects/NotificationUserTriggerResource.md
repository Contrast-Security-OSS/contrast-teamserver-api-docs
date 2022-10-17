## NotificationUserTriggerResource
---
### Description
Notification User Trigger Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_asset_types | Enabled for all asset types | boolean |  | false |
| all_attack_status | Enabled for all attack status | boolean |  | false |
| all_rule_severities | Enabled for all vulnerability severities | boolean |  | false |
| all_server_environments | Enabled for all server environments | boolean |  | false |
| asset_types | List of asset types configured | set |  | false |
| attack_status | List of attack status configured | set |  | false |
| channels | List of channels configured | list |  | false |
| notification_type | Notification type | notificationtrigger |  | false |
| notify_on_change | Notify on status change | boolean |  | false |
| rule_severities | List of rule severities configured | set |  | false |
| server_environments | List of server environments | set |  | false |
### Template
```
{"all_asset_types":true,"all_attack_status":true,"all_rule_severities":true,"all_server_environments":true,"asset_types":[],"attack_status":[],"channels":[],"links":[],"notify_on_change":true,"rule_severities":[],"server_environments":[],"notification_type":""}
```

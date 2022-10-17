## AttackMonitorTopApplicationResource
---
### Description
RASP Attack Monitor Top Application Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_id | Application ID | string |  | false |
| application | Application Name | string |  | false |
| blocked_attacks | Number of Blocked Attacks | long |  | false |
| exploited_attacks | Number of Exploited Attacks | long |  | false |
| importance | Application Importance | applicationimportance |  | false |
| probed_attacks | Number of Probed Attacks | long |  | false |
| suspicious_attacks | Number of Suspicious Attacks | long |  | false |
| total_attacks | Number of Total Attacks | long |  | false |
### Template
```
{"app_id":"","application":"","blocked_attacks":0,"exploited_attacks":0,"importance":"","probed_attacks":0,"suspicious_attacks":0,"total_attacks":0}
```

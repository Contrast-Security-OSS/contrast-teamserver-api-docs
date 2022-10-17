## RemediationPolicyResource
---
### Description
Remediation policy Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| action | Action taken by remediation policy on vulnerabilities in violation | action |  | false |
| all_applications | Apply to all applications | boolean |  | false |
| all_rules | Apply to all rules | boolean |  | false |
| all_server_environments | Apply to all server environments | boolean |  | false |
| application_importance | List of application importance | set |  | false |
| applications | List of applications | list |  | false |
| enabled | Is enabled? | boolean |  | false |
| name | Remediation policy name | string |  | false |
| policy_id | Remediation policy ID | long |  | false |
| remediation days | Remediation days | int |  | false |
| route_based_enabled | Is route-based configuration enabled? | boolean |  | false |
| rule_severities | List of rule severities | set |  | false |
| rules | List of rules | list |  | false |
| server_environments | List of server environments | list |  | false |
| time_based_enabled | Is time-based configuration enabled? | boolean |  | false |
| valid | Is policy valid? | boolean |  | false |
### Template
```
{"action":"","all_applications":true,"all_rules":true,"all_server_environments":true,"application_importance":[],"applications":[],"enabled":true,"links":[],"name":"","policy_id":0,"remediation days":0,"route_based_enabled":true,"rule_severities":[],"rules":[],"server_environments":[],"time_based_enabled":true,"valid":true}
```

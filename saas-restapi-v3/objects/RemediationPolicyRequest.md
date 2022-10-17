## RemediationPolicyRequest
---
### Description
Remediation Policy Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| action | Action | action |  | false |
| all_applications | Apply to all applications? | boolean |  | false |
| all_rules | Apply to all rules? | boolean |  | false |
| all_server_environments | Apply to all server environments? | boolean |  | false |
| application_importance | List of Application Importance | set |  | false |
| applications | List of Applications | set |  | false |
| name | Name | string |  | false |
| remediation_days | Time based remediation policy days | integer |  | true |
| route_based_enabled | Is route based policy enabled? | boolean |  | false |
| rule_severities | List of Rule Severities | set |  | false |
| rules | List of Rules | set |  | false |
| server_environments | List of Server Environments | set |  | false |
### Template
```
{"action":"","all_applications":true,"all_rules":true,"all_server_environments":true,"application_importance":[],"applications":[],"name":"","remediation_days":0,"route_based_enabled":true,"rule_severities":[],"rules":[],"server_environments":[]}
```

## RemediationPolicyResponse
---
### Description
Remediation policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| policy | Remediation Policy | RemediationPolicyResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"policy":{"action":"","all_applications":true,"all_rules":true,"all_server_environments":true,"application_importance":[],"applications":[],"enabled":true,"links":[],"name":"","policy_id":0,"remediation days":0,"route_based_enabled":true,"rule_severities":[],"rules":[],"server_environments":[],"time_based_enabled":true,"valid":true},"success":true}
```

## TraceRemediationPolicyViolationItem
---
### Description
Trace remediation policy violations
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| traces | List of vulnerability UUIDs | set |  | false |
| violation | Remediation Policy violation | RemediationPolicyResource |  | false |
### Template
```
{"links":[],"traces":[],"violation":{"action":"","all_applications":true,"all_rules":true,"all_server_environments":true,"application_importance":[],"applications":[],"enabled":true,"links":[],"name":"","policy_id":0,"remediation days":0,"route_based_enabled":true,"rule_severities":[],"rules":[],"server_environments":[],"time_based_enabled":true,"valid":true}}
```

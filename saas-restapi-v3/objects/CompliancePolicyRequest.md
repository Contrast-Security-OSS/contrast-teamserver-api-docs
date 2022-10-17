## CompliancePolicyRequest
---
### Description
Compliance Policy Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Apply to all applications? | boolean |  | false |
| all_rules | Apply to all rules? | boolean |  | false |
| application_importance | List of Application Importance | set |  | false |
| applications | List of Applications | set |  | false |
| name | Name | string |  | false |
| rule_severities | List of Rule Severities | set |  | false |
| rules | List of Rules | set |  | false |
| standards | List of security standards | list |  | false |
### Template
```
{"all_applications":true,"all_rules":true,"application_importance":[],"applications":[],"name":"","rule_severities":[],"rules":[],"standards":[]}
```

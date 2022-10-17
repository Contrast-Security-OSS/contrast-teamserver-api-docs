## CompliancePolicyResource
---
### Description
Compliance policy Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Apply to all applications | boolean |  | false |
| all_rules | Apply to all rules | boolean |  | false |
| application_importance | List of application importance | set |  | false |
| applications | List of applications | list |  | false |
| enabled | Is enabled? | boolean |  | false |
| key | Compliance policy key | string |  | false |
| name | Compliance policy shortened name | string |  | false |
| policy_id | Compliance policy id | long |  | false |
| readonly | Is readonly policy? | boolean |  | false |
| rule_severities | List of rule severities | set |  | false |
| rules | List of rules | list |  | false |
| standards | List of security standards | list |  | false |
| valid | Is policy valid? | boolean |  | false |
### Template
```
{"all_applications":true,"all_rules":true,"application_importance":[],"applications":[],"enabled":true,"key":"","links":[],"name":"","policy_id":0,"readonly":true,"rule_severities":[],"rules":[],"standards":[],"valid":true}
```

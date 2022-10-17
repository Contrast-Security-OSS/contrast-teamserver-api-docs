## CompliancePolicyResponse
---
### Description
Compliance policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| policy | Compliance Policy | CompliancePolicyResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"policy":{"all_applications":true,"all_rules":true,"application_importance":[],"applications":[],"enabled":true,"key":"","links":[],"name":"","policy_id":0,"readonly":true,"rule_severities":[],"rules":[],"standards":[],"valid":true},"success":true}
```

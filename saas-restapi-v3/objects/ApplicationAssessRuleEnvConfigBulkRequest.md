## ApplicationAssessRuleEnvConfigBulkRequest
---
### Description
Application Assess Rule Environment Configuration Bulk Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| dev_enabled | Is development enabled | boolean |  | false |
| prod_enabled | Is production enabled | boolean |  | false |
| qa_enabled | Is QA enabled | boolean |  | false |
| rule_names | List of rule names | list |  | false |
### Template
```
{"dev_enabled":true,"prod_enabled":true,"qa_enabled":true,"rule_names":[]}
```

## ApplicationAssessRuleEnvConfigRequest
---
### Description
Application Assess Rule Environment Configuration Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| enabled | Is environment enabled | boolean |  | false |
| environment | Server Environment | serverenvironment |  | false |
| rule_name | Rule name | string |  | false |
### Template
```
{"enabled":true,"environment":"","rule_name":""}
```

## ApplicationAssessRuleEnvConfigResource
---
### Description
Application Assess Rule Environment Configuration Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| dev_enabled | Assess rule enabled for develop environment | boolean |  | false |
| prod_enabled | Assess rule enabled for production environment | boolean |  | false |
| qa_enabled | Assess rule enabled for QA environment | boolean |  | false |
| ruleSeverityLabel | Translated Rule Severity | string |  | false |
| rule_description | Rule description | string |  | false |
| rule_name | Rule name | string |  | false |
| rule_severity | Rule Severity | string |  | false |
| rule_title | Rule title | string |  | false |
### Template
```
{"dev_enabled":true,"links":[],"prod_enabled":true,"qa_enabled":true,"rule_description":"","rule_name":"","rule_severity":"","ruleSeverityLabel":"","rule_title":""}
```

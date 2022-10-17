## RuleDrilldownResource
---
### Description
Rule Drilldown Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application Resource | ApplicationBaseResource |  | false |
| dev_enabled | Assess rule enabled for develop environment | boolean |  | false |
| has_dev_servers | The application has development servers | boolean |  | false |
| has_prod_servers | The application has production servers | boolean |  | false |
| has_qa_servers | The application has qa servers | boolean |  | false |
| prod_enabled | Assess rule enabled for production environment | boolean |  | false |
| qa_enabled | Assess rule enabled for QA environment | boolean |  | false |
### Template
```
{"application":{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0},"dev_enabled":true,"has_dev_servers":true,"has_prod_servers":true,"has_qa_servers":true,"links":[],"prod_enabled":true,"qa_enabled":true}
```

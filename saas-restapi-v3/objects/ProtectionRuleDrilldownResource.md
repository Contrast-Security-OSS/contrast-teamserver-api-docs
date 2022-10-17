## ProtectionRuleDrilldownResource
---
### Description
Protection Rule Env Config Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| allowed_roles | The Allowed Application Roles | collection |  | false |
| app_id | Application ID | string |  | false |
| app_name | Application ID | string |  | false |
| development | Rule Configuration for development servers | blockingmode |  | false |
| has_dev_servers | The application has development servers | boolean |  | false |
| has_prod_servers | The application has production servers | boolean |  | false |
| has_protection_dev_servers | The application has protection in development servers | boolean |  | false |
| has_qa_servers | The application has qa servers | boolean |  | false |
| importance | Application Importance | string |  | false |
| master | Is application master | boolean |  | false |
| primary | Is application primary | boolean |  | false |
| production | Rule Configuration for production servers | blockingmode |  | false |
| qa | Rule Configuration for qa servers | blockingmode |  | false |
| total_modules | Number of app modules | long |  | false |
### Template
```
{"allowed_roles":[],"app_id":"","app_name":"","development":"","has_dev_servers":true,"has_prod_servers":true,"has_protection_dev_servers":true,"has_qa_servers":true,"importance":"","links":[],"master":true,"primary":true,"production":"","qa":"","total_modules":0}
```

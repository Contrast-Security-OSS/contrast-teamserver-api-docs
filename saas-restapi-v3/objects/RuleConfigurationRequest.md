## RuleConfigurationRequest
---
### Description
Request to enabled/disabled the rule in each one of the environments
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| productionEnabled | Value of the rule in the Production environment | boolean |  | false |
| developmentEnabled | Value of the rule in the Development environment | boolean |  | false |
| qaEnabled | Value of the rule in the QA environment | boolean |  | false |
### Template
```
{"developmentEnabled":true,"productionEnabled":true,"qaEnabled":true}
```

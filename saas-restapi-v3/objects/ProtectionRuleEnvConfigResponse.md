## ProtectionRuleEnvConfigResponse
---
### Description
Protection Rule Enviroment Configuration Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| rule | Protection Rule | ProtectionRuleEnvConfigResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"errors":[],"messages":[],"rule":{"cves":[],"description":"","devMode":0,"links":[],"mode":"","name":"","prodMode":0,"protectionRuleUuid":"","qaMode":0,"ruleId":0,"triggered":0},"success":true}
```

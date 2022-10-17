## ProtectionRuleExceptionResponse
---
### Description
Protection Rule Exception Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| exception | Exception | RuleExclusionResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"errors":[],"exception":{"all_assessment_rules":true,"all_protection_rules":true,"all_rules":true,"assess":true,"assess_rules":[],"codes":[],"defend":true,"exception_id":0,"queue_pattern_type":"","input_name":"","input_type":"","links":[],"name":"","protection_rules":[],"queues":[],"type":"","url_pattern_type":"","urls":[]},"messages":[],"success":true}
```

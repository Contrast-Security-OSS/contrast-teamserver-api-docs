## RuleExclusionRequest
---
### Description
Rule Exclusion Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_assessment_rules | All Assessment Rules | boolean |  | false |
| all_protection_rules | All Protection Rules | boolean |  | false |
| all_rules | All Rules | boolean |  | false |
| assessment_rules | List of Assessment Rules | array |  | false |
| codes | Codes | array |  | false |
| event_uuid | Attack Event ID | string |  | false |
| input_name | Name | string |  | false |
| input_type | Exception Type | exclusioninputtype |  | false |
| name | Name | string |  | false |
| protection_rules | List of Protection Rules | array |  | false |
| queue_pattern_type | Queue Pattern Type | exclusionqueuepatterntype |  | false |
| queues | Queues names | array |  | false |
| type | Exception Type | exclusiontype |  | true |
| url_pattern_type | URL Pattern Type | exclusionurlpattern |  | false |
| urls | URLs | array |  | false |
### Template
```
{"all_assessment_rules":true,"all_protection_rules":true,"all_rules":true,"assessment_rules":[],"codes":[],"event_uuid":"","queue_pattern_type":"","input_name":"","input_type":"","name":"","protection_rules":[],"queues":[],"type":"","url_pattern_type":"","urls":[]}
```

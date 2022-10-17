## OrgRuleExclusionResource
---
### Description
Organization Rule Exclusion Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_assessment_rules | All Assessment Rules | boolean |  | false |
| all_protection_rules | All Protection Rules | boolean |  | false |
| all_rules | All Rules (IAST and RASP) | boolean |  | false |
| application | Application | ApplicationBaseResource |  | false |
| assess | Assess mode enabled | boolean |  | false |
| assess_rules | List of Assessment Rules | list |  | false |
| codes | Codes | collection |  | false |
| defend | Defend mode enabled | boolean |  | false |
| exception_id | Exception ID | long |  | false |
| input_name | Name | string |  | false |
| input_type | Exception Type | exclusioninputtype |  | false |
| name | Name | string |  | false |
| protection_rules | List of Protection Rules | list |  | false |
| queue_pattern_type | Queue Pattern Type | exclusionqueuepatterntype |  | false |
| queues | Queues names | collection |  | false |
| type | Exception Type | exclusiontype |  | false |
| url_pattern_type | URL Pattern Type | exclusionurlpattern |  | false |
| urls | URLs | collection |  | false |
### Template
```
{"all_assessment_rules":true,"all_protection_rules":true,"all_rules":true,"application":{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0},"assess":true,"assess_rules":[],"codes":[],"defend":true,"exception_id":0,"queue_pattern_type":"","input_name":"","input_type":"","links":[],"name":"","protection_rules":[],"queues":[],"type":"","url_pattern_type":"","urls":[]}
```

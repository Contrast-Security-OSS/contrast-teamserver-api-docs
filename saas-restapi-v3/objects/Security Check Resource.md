## Security Check Resource
---
### Description
Security Check Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agent_language | Agent Language | agentlanguage |  | false |
| application_id | Application ID | string |  | false |
| application_name | Application Name | string |  | false |
| id | The id of the security check | long |  | false |
| job_outcome_policy | Job Outcome Policy | Job Outcome Policy Resource |  | false |
| job_start_time | Job Start Time | long |  | false |
| origin | Origin | string |  | false |
| result | Result | boolean |  | false |
### Template
```
{"agent_language":"","application_id":"","application_name":"","job_outcome_policy":{"all_applications":true,"all_environments":true,"all_rules":true,"all_rules_threshold":0,"app_criterion":"","application_tags":[],"applications":[],"custom_end_date":true,"custom_start_date":true,"enabled":true,"end_date":0,"environment":[],"importance":[],"include_all_start_dates":true,"include_rules":true,"is_job_start_time":true,"keycode":"","links":[],"name":"","opt_into_query":true,"organization_id":0,"outcome":"","policy_id":0,"rule_severities":[],"rules":{},"severities":{},"start_date":0,"status_filter":[]},"job_start_time":0,"links":[],"origin":"","result":true,"id":0}
```

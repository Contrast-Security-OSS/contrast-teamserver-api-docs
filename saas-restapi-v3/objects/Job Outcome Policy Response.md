## Job Outcome Policy Response
---
### Description
Job Outcome Policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"errors":[],"messages":[],"policy":{"all_applications":true,"all_environments":true,"all_rules":true,"all_rules_threshold":0,"app_criterion":"","application_tags":[],"applications":[],"custom_end_date":true,"custom_start_date":true,"enabled":true,"end_date":0,"environment":[],"importance":[],"include_all_start_dates":true,"include_rules":true,"is_job_start_time":true,"keycode":"","links":[],"name":"","opt_into_query":true,"organization_id":0,"outcome":"","policy_id":0,"rule_severities":[],"rules":{},"severities":{},"start_date":0,"status_filter":[]},"success":true}
```

## Job Outcome Policy Request
---
### Description
Job Outcome Policy Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Policy is applied to all applictions | boolean |  | false |
| all_environments | Consider all environments | boolean |  | false |
| all_rules | Consider all rules | boolean |  | false |
| all_rules_threshold | Threshold for when all rules is true | long |  | false |
| app_criterion | Criteria to select the applications to apply the policy | applicationcriterion |  | true |
| app_ids | Applications for which the policy is applied | list |  | false |
| application_tags | Application tags for which the policy is applied | list |  | false |
| custom_end_date | Policy has a custom end date | boolean |  | false |
| custom_start_date | Policy has a custom start date | boolean |  | false |
| enabled | Policy is considered for calculation | boolean |  | false |
| end_date | Vulnerability end date to be considered | long |  | false |
| environments | Server environments of applications for which the policy is applied | list |  | false |
| importances | Importances of applications for which the policy is applied | list |  | false |
| include_all_start_dates | Consider all start dates | boolean |  | false |
| include_rules | Include or exclude rules in the rules list | boolean |  | false |
| is_job_start_time | Policy is using job start time as start date | boolean |  | false |
| keycode | job outcome policy keycode | string |  | false |
| name | Job Outcome Policy Name | string |  | false |
| opt_into_query | If the query by filters send by the job should be considered, default false | boolean |  | false |
| outcome | Outcome of the job when policy is failed | outcome |  | true |
| rule_severities | severities of rules to be considered | list |  | false |
| rules | Rules included or excluded in the calculation | map |  | false |
| severities | Severities and threshold used for calculation | map |  | false |
| start_date | Vulnerability start date to be considered | long |  | false |
| status_filter | Statuses that are included in the calculation | list |  | false |
### Template
```
{"all_applications":true,"all_environments":true,"all_rules":true,"all_rules_threshold":0,"app_criterion":"","app_ids":[],"application_tags":[],"custom_end_date":true,"custom_start_date":true,"enabled":true,"end_date":0,"environments":[],"importances":[],"include_all_start_dates":true,"include_rules":true,"is_job_start_time":true,"keycode":"","name":"","opt_into_query":true,"outcome":"","rule_severities":[],"rules":{},"severities":{},"start_date":0,"status_filter":[]}
```

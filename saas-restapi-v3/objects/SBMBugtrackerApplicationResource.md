## SBMBugtrackerApplicationResource
---
### Description
 SBM Bugtracker Application Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Is all applications selected? | boolean |  | false |
| app_criterion | Is applications configuration option selected? | boolean |  | false |
| application_criterion | Indicates the type of application criterion used for filtering | applicationcriterion |  | false |
| applications | List of applications | list |  | false |
| bugtracker_id | Bugtracker ID | long |  | false |
| connection_unavailable | Has troubles with connection? | boolean |  | false |
| contrast_product | The product for which bugtracker application is configured | contrastproduct |  | false |
| full_integration | Is full integration active? | boolean |  | false |
| has_two_way_integration | Has Two way integration configured? | boolean |  | false |
| host | Hostname | string |  | false |
| importance | List of application importances | list |  | false |
| keycode | Bugtracker keycode | string |  | false |
| name | Name | string |  | false |
| project_id | Project ID | long |  | false |
| serverless_account_ids | List of serverless account ids | set |  | false |
| serverless_categories | List of serverless categories | set |  | false |
| type | Bugtracker type | string |  | false |
| username | Username | string |  | false |
### Template
```
{"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"bugtracker_id":0,"keycode":"","type":"","connection_unavailable":true,"contrast_product":"","full_integration":true,"has_two_way_integration":true,"host":"","importance":[],"links":[],"name":"","project_id":0,"serverless_account_ids":[],"serverless_categories":[],"username":""}
```

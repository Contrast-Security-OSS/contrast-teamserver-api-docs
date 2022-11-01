## BugzillaBugtrackerApplicationResource
---
### Description
Bugzilla Bugtracker Application Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | Is all applications selected? | boolean |  | false |
| app_criterion | Is applications configuration option selected? | boolean |  | false |
| application_criterion | Indicates the type of application criterion used for filtering | applicationcriterion |  | false |
| applications | List of applications | list |  | false |
| bugtracker_id | Bugtracker ID | long |  | false |
| component | Component name | string |  | false |
| connection_unavailable | Has troubles with connection? | boolean |  | false |
| contrast_product | The product for which bugtracker application is configured | contrastproduct |  | false |
| deployment_mode | Bug tracker deployment mode | string |  | false |
| full_integration | Is full integration active? | boolean |  | false |
| has_two_way_integration | Has Two way integration configured? | boolean |  | false |
| host | Hostname | string |  | false |
| importance | List of application importances | list |  | false |
| keycode | Bugtracker keycode | string |  | false |
| name | Name | string |  | false |
| priority | Priority | string |  | false |
| product | Product name | string |  | false |
| serverless_account_ids | List of serverless account ids | set |  | false |
| serverless_categories | List of serverless categories | set |  | false |
| type | Bugtracker type | string |  | false |
| username | Username | string |  | false |
| version | Version | string |  | false |
### Template
```
{"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"bugtracker_id":0,"keycode":"","type":"","component":"","connection_unavailable":true,"contrast_product":"","deployment_mode":"","full_integration":true,"has_two_way_integration":true,"host":"","importance":[],"links":[],"name":"","priority":"","product":"","serverless_account_ids":[],"serverless_categories":[],"username":"","version":""}
```

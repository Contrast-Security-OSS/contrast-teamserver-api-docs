## VSTSBugtrackerFieldsResource
---
### Description
VSTS Bugtracker Fields Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| add_prefix_to_issue_title | If enabled, it adds the application name as a prefix to the vulnerability issue title | boolean |  | false |
| all_applications | All applications selected | boolean |  | false |
| app_criterion | Are we choosing by application name (true) or application importance (false) | boolean |  | false |
| application_criterion | Indicates the type of criterion for the application | applicationcriterion |  | false |
| applications | List of application Ids | list |  | false |
| area | Team area | string |  | false |
| assignee | Assignee | string |  | true |
| auto_create_tickets_all_rules | Whether all rules selected for creating tickets automatically | boolean |  | false |
| auto_create_tickets_enabled | Whether creating tickets automatically is enabled | boolean |  | false |
| auto_create_tickets_rules | List of rules for creating tickets automatically | list |  | false |
| auto_create_tickets_severities | List of rule severities for creating tickets automatically | set |  | false |
| bugtracker_id | Bugtracker ID | long |  | false |
| credentials | Credentials set | BugtrackerCredentialsResource |  | false |
| exclude_sensitive_info | Exclude bug tracker sensitive info | boolean |  | false |
| host | Host | string |  | false |
| importance | app importance | list |  | false |
| issue_type | Default issue type | string |  | false |
| name | Bugtracker Name | string |  | false |
| priority_critical | Priority critical | string |  | false |
| priority_field_available | Is priority field available? | boolean |  | false |
| priority_high | Priority high | string |  | false |
| priority_low | Priority low | string |  | false |
| priority_medium | Priority medium | string |  | false |
| priority_note | Priority note | string |  | false |
| project | Project | string |  | false |
| send_tags | Show vulnerability tags in the bug tracker | boolean |  | false |
| team | Project team | string |  | false |
| username | Username | string |  | false |
| version | Version | string |  | false |
### Template
```
{"add_prefix_to_issue_title":true,"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"area":"","assignee":"","auto_create_tickets_all_rules":true,"auto_create_tickets_enabled":true,"auto_create_tickets_severities":[],"auto_create_tickets_rules":[],"bugtracker_id":0,"credentials":{},"exclude_sensitive_info":true,"host":"","importance":[],"issue_type":"","links":[],"name":"","priority_critical":"","priority_field_available":true,"priority_high":"","priority_low":"","priority_medium":"","priority_note":"","project":"","send_tags":true,"team":"","username":"","version":""}
```

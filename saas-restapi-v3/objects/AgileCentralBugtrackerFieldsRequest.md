## AgileCentralBugtrackerFieldsRequest
---
### Description
Agile Central Bugtracker Fields Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | All applications selected | boolean |  | false |
| app_criterion | Application importance or applications selected | boolean |  | false |
| applications | List of application Ids | list |  | false |
| assignee | Assignee | string |  | true |
| auto_create_tickets_all_rules | Whether all rules selected for creating tickets automatically | boolean |  | false |
| auto_create_tickets_enabled | Whether creating tickets automatically is enabled | boolean |  | false |
| auto_create_tickets_rules | List of rules for creating tickets automatically | list |  | false |
| auto_create_tickets_severities | List of rule severities for creating tickets automatically | set |  | false |
| bugtracker_id | Bugtracker ID | long |  | false |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| fields | List of Agile Central fields | list |  | false |
| host | Host | string |  | false |
| importance | app importance | list |  | false |
| issue_type | Default issue type | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| priority_critical | Priority critical | string |  | false |
| priority_field_available | Is priority field available? | boolean |  | false |
| priority_high | Priority high | string |  | false |
| priority_low | Priority low | string |  | false |
| priority_medium | Priority medium | string |  | false |
| priority_note | Priority note | string |  | false |
| project | Project | string |  | false |
| username | Username | string |  | false |
### Template
```
{"all_applications":true,"app_criterion":true,"applications":[],"assignee":"","auto_create_tickets_all_rules":true,"auto_create_tickets_enabled":true,"auto_create_tickets_severities":[],"auto_create_tickets_rules":[],"bugtracker_id":0,"credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","fields":[],"host":"","importance":[],"issue_type":"","name":"","password":"","priority_critical":"","priority_field_available":true,"priority_high":"","priority_low":"","priority_medium":"","priority_note":"","project":"","username":""}
```

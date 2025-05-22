## VSTSBugtrackerResponse
---
### Description
VSTS Bugtracker Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker | VSTS configuration | VSTSBugtrackerFieldsResource |  | false |
| errors | List of errors | list |  | false |
| integrations | List of VSTS Two Way Integration conditions | collection |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"bugtracker":{"add_prefix_to_issue_title":true,"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"area":"","assignee":"","auto_create_tickets_all_rules":true,"auto_create_tickets_enabled":true,"auto_create_tickets_severities":[],"auto_create_tickets_rules":[],"bugtracker_id":0,"credentials":{},"exclude_sensitive_info":true,"host":"","importance":[],"issue_type":"","links":[],"name":"","priority_critical":"","priority_field_available":true,"priority_high":"","priority_low":"","priority_medium":"","priority_note":"","project":"","send_tags":true,"team":"","username":"","version":""},"errors":[],"integrations":[],"messages":[],"success":true}
```

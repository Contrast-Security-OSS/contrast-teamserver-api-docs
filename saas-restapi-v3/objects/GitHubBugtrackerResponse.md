## GitHubBugtrackerResponse
---
### Description
GitHub Bugtracker Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker | GitHub Configuration | GitHubBugtrackerFieldsResource |  | false |
| messages | List of messages | list |  | false |
| settings | Settings of GitHub bugtracker | GitHubBugtrackerOrganizationsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"bugtracker":{"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"assignee":"","assignees":[],"auth_type":"","auto_create_tickets_all_rules":true,"auto_create_tickets_enabled":true,"auto_create_tickets_severities":[],"auto_create_tickets_rules":[],"bugtracker_id":0,"credentials":{},"host":"","importance":[],"issue_type":"","labels":[],"links":[],"milestone":0,"name":"","priority_critical":"","priority_field_available":true,"priority_high":"","priority_low":"","priority_medium":"","priority_note":"","project":"","username":""},"messages":[],"settings":{"organizations":[],"selected_organization":{"organization":"","repositories":[],"repository_settings":{"assignees":[],"labels":[],"milestones":[],"repository":""}}},"success":true}
```

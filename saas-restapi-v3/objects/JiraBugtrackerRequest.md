## JiraBugtrackerRequest
---
### Description
Jira Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_users | JIRA all matching users | boolean |  | false |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| epic_search | Search JIRA for matching epics | string |  | false |
| host | Host | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| user_search | Search JIRA for matching users | string |  | false |
| username | Username | string |  | false |
### Template
```
{"all_users":true,"credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","epic_search":"","host":"","name":"","password":"","user_search":"","username":""}
```

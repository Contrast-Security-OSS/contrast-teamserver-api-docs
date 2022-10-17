## SBMBugtrackerRequest
---
### Description
SBM Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applications | List of application ids | list |  | false |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| host | Host | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| project_id | Project ID | long |  | false |
| username | Username | string |  | false |
### Template
```
{"applications":[],"credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","host":"","name":"","password":"","project_id":0,"username":""}
```

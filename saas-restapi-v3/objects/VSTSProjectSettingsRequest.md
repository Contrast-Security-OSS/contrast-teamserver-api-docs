## VSTSProjectSettingsRequest
---
### Description
VSTS Project Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| host | Host | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| project | Project name | string |  | false |
| username | Username | string |  | false |
| version | Bugtracker version | vstsversion |  | false |
### Template
```
{"credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","host":"","name":"","password":"","project":"","username":"","version":""}
```

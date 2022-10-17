## BugzillaBugtrackerRequest
---
### Description
Bugzilla Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applications | List of application ids | list |  | false |
| component | Component name | string |  | true |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| host | Host | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| priority | Priority | string |  | true |
| product | Product name | string |  | true |
| username | Username | string |  | false |
| version | Version | string |  | true |
### Template
```
{"applications":[],"component":"","credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","host":"","name":"","password":"","priority":"","product":"","username":"","version":""}
```

## BugtrackerCredentialsRequest
---
### Description
Bugtracker Credentials Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| credentials_update | Indicates if an existing credentials will be updated with this fields | boolean |  | false |
| host | Bugtracker host | string |  | false |
| name | Bugtracker credentials name | string |  | false |
| password | Password | string |  | false |
| username | Username | string |  | false |
### Template
```
{"credentials_update":true,"host":"","name":"","password":"","username":""}
```

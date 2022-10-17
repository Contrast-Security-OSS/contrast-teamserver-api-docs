## GitHubBugtrackerRequest
---
### Description
GitHub Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| auth_type | GitHub authentication type | githubauthtype |  | true |
| credentials | New set of Bugtracker credentials | BugtrackerCredentialsRequest |  | false |
| credentials_id | Id of the used credentials set | string |  | false |
| github_org | GitHub organization name | string |  | false |
| host | Host | string |  | false |
| name | Bugtracker Name | string |  | false |
| password | Password | string |  | false |
| repository | GitHub repository name | string |  | false |
| username | Username | string |  | false |
### Template
```
{"auth_type":"","credentials":{"credentials_update":true,"host":"","name":"","password":"","username":""},"credentials_id":"","github_org":"","host":"","name":"","password":"","repository":"","username":""}
```

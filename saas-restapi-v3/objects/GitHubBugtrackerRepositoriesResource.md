## GitHubBugtrackerRepositoriesResource
---
### Description
GitHub Bugtracker Repositories Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| organization | GitHub organization that owns these resources | string |  | false |
| repositories | List of GitHub repositories | list |  | false |
| repository_settings | Selected repository integration settings | GitHubBugtrackerSettingsResource |  | false |
### Template
```
{"organization":"","repositories":[],"repository_settings":{"assignees":[],"labels":[],"milestones":[],"repository":""}}
```

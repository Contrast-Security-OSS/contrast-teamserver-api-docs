## GitHubBugtrackerOrganizationsResource
---
### Description
GitHub Bugtracker Organizations Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| organizations | List of user&#x27;s GitHub organizations | list |  | false |
| selected_organization | Selected organization with its repository list | GitHubBugtrackerRepositoriesResource |  | false |
### Template
```
{"organizations":[],"selected_organization":{"organization":"","repositories":[],"repository_settings":{"assignees":[],"labels":[],"milestones":[],"repository":""}}}
```

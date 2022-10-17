## GitHubBugtrackerSettingsResource
---
### Description
GitHub Bugtracker Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assignees | List of GitHub repository assignees | list |  | false |
| labels | List of GitHub repository labels | list |  | false |
| milestones | List of GitHub repository milestones | list |  | false |
| repository | GitHub repository that owns these resources | string |  | false |
### Template
```
{"assignees":[],"labels":[],"milestones":[],"repository":""}
```

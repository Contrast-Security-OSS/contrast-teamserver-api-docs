## TraceBugtrackerRequest
---
### Description
Trace Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agile_central_fields | List of Agile Central issue fields | list |  | false |
| assignee | Assignee | string |  | false |
| bugtracker_issue_type | Default issue type | string |  | false |
| confirmed | Confirmed | boolean |  | true |
| epic_id | Jira epic id | string |  | false |
| fields | List of customized fields | list |  | false |
| first | First | boolean |  | true |
| github_fields | GitHub issue fields | GitHubFieldsResource |  | false |
| httpRequest | HTTP request | boolean |  | true |
| intermediate | Intermediate | boolean |  | true |
| last | Last | boolean |  | true |
| priority | Priority | string |  | false |
| recommendation | Recommendation | boolean |  | true |
| references | References | boolean |  | true |
| risk | Risk | boolean |  | true |
| traces | Vulnerability/Instance UUIDs | list |  | true |
### Template
```
{"agile_central_fields":[],"assignee":"","bugtracker_issue_type":"","confirmed":true,"epic_id":"","fields":[],"first":true,"github_fields":{"assignees":[],"labels":[],"milestone":0},"httpRequest":true,"intermediate":true,"last":true,"priority":"","recommendation":true,"references":true,"risk":true,"traces":[]}
```

## RuleDrilldownResponse
---
### Description
Rule Drilldown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| configs | List of assess rules environment configuration by application | list |  | false |
| description | Description | string |  | false |
| languages | List of languages supported | list |  | false |
| messages | List of messages | list |  | false |
| name | Rule Name | string |  | false |
| severity | Rule Severity | string |  | false |
| severityLabel | Translated Rule Severity | string |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| title | Rule Title | string |  | false |
### Template
```
{"configs":[],"description":"","languages":[],"messages":[],"name":"","severity":"","severityLabel":"","success":true,"title":""}
```

## ApprovalWorkflowSettingsResponse
---
### Description
Approval workflow settings response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| enabled | Whether approval workflow is enabled or not | boolean |  | false |
| messages | List of messages | list |  | false |
| severities | List of rule severities configured | list |  | false |
| status | List of vulnerability status | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"enabled":true,"messages":[],"severities":[],"status":[],"success":true}
```

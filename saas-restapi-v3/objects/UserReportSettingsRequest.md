## UserReportSettingsRequest
---
### Description
User Report Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| footer | Custom footer | string |  | false |
| include_notes | Include notes | boolean |  | false |
| include_status | Include status | boolean |  | false |
| severities | List of Rule Severities | collection |  | false |
| statuses | List of statuses | collection |  | false |
| tags | List of tags | collection |  | false |
| types | List of types | collection |  | true |
### Template
```
{"footer":"","include_notes":true,"include_status":true,"severities":[],"statuses":[],"tags":[],"types":[]}
```

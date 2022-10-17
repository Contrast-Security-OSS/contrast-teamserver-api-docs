## UserReportPreferencesResponse
---
### Description
User Report Preferences Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| custom_footer | Custom footer | string |  | false |
| include_notes | Include notes | boolean |  | false |
| include_status | Include status | boolean |  | false |
| messages | List of messages | list |  | false |
| severities | List of severities | collection |  | false |
| statuses | List of statuses | collection |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| tags | List of tags | collection |  | false |
| types | List of types | collection |  | false |
### Template
```
{"custom_footer":"","include_notes":true,"include_status":true,"messages":[],"severities":[],"statuses":[],"success":true,"tags":[],"types":[]}
```

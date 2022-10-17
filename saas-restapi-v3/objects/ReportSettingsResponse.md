## ReportSettingsResponse
---
### Description
Report Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| settings | Report settings Resource | ReportSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"settings":{"custom_footer":"","include_notes":true,"includeStatus":true,"severities":[],"status":[],"tags":[],"types":[]},"success":true}
```

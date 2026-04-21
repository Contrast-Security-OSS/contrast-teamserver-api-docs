## VSTSProjectSettingsResponse
---
### Description
VSTS Project Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker_errors | List of bugtracker errors | list |  | false |
| error_code | Status returned from bugtracker | integer |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| projects | VSTS project settings | VSTSProjectSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"bugtracker_errors":[],"error_code":0,"errors":[],"messages":[],"projects":{"work_item_types":[]},"success":true}
```

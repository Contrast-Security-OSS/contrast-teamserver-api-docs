## AuthSettingsResponse
---
### Description
Authentication Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| managing_users | TS controls the users | boolean |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| user_attribute | User attribute | string |  | false |
### Template
```
{"managing_users":true,"messages":[],"success":true,"user_attribute":""}
```

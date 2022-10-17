## AuthModeResponse
---
### Description
Authentication Mode Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| auth_mode | Authentication mode | authenticationmode |  | false |
| messages | List of messages | list |  | false |
| properties | Properties map | map |  | false |
| skip_user_validation | Skip user validation preference | boolean |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"auth_mode":"","messages":[],"properties":{},"skip_user_validation":true,"success":true}
```

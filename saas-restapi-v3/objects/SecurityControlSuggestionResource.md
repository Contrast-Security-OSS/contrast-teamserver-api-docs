## SecurityControlSuggestionResource
---
### Description
Security Control Suggestion Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| api | API | string |  | false |
| applications | A subset of applications that suggested this control | list |  | false |
| apps | Applications that suggested this control. Use applications field instead. | list |  | false |
| language | Language | string |  | false |
| module | Module | string |  | false |
| name | Name | string |  | false |
| pattern | Pattern | string |  | false |
| suggestion_id | ID | long |  | false |
| total_apps | The total number of applications that suggested this control | integer |  | false |
| type | Type | securitycontroltype |  | false |
| user_exists | If the user that suggest this still exists | boolean |  | false |
| username | Username that suggested the security control | string |  | false |
### Template
```
{"api":"","applications":[],"apps":[],"language":"","links":[],"module":"","name":"","pattern":"","suggestion_id":0,"total_apps":0,"type":"","user_exists":true,"username":""}
```

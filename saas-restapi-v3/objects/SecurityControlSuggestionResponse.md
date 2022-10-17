## SecurityControlSuggestionResponse
---
### Description
Security Control Suggestion Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| suggestion | Security controls suggestions | SecurityControlSuggestionResource |  | false |
### Template
```
{"messages":[],"success":true,"suggestion":{"api":"","apps":[],"language":"","links":[],"module":"","name":"","pattern":"","suggestion_id":0,"type":"","user_exists":true,"username":""}}
```
